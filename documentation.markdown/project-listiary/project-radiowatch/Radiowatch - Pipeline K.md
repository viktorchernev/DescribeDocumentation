---
layout: page
title: Radiowatch - Pipeline K
permalink: /listiary/radiowatch/pipeline-k/
exclude: true
---
<br>
Radiowatch is a listiary wiki. And a one that writes itself, at that. At least to an extent.
What we mean is that there are bots that track radio station streams, recognize music, and auto-generate new articles - on invocation, or on a timer.
In this article we will explore how those bots work.
<br>
There are two paths to the radiowatch automation back end - 'K' and 'W'.
K stands for knowledge, while W stands for web. The knowledge path is about creating a database of knowledge about different songs, including the actual songs themselves in some file format, non-compressed if possible, links to said songs on different platforms like youtube and soundcloud, and names used for said songs on different radio streams, and why not, on the different platforms, like youtube and soundcloud. The 'W' path is all about creating and uploading the actual articles for the wiki.
<br>
<br>


## K1. Ripping

`streamripper-rip.bat`  
`streamripper-rip-debug.bat`  
  
The first step in acquiring knowledge is ripping radio streams. We find out the URLs of the web streams of radio stations and we run a command line utility - Streamripper, which listens to a stream and writes the data being streamed to our hard disk, splitting the data to tracks, based on the metadata being broadcasted with the stream. This is not pitch-perfect, but has proven to work reliably and well. 

We need to keep in mind though, that in radio broadcasts there are overlapping sounds - songs and effects and radio-hosts talking over. So, we get some of that in our dumps, but it is not a problem, as long as the metadata being broadcasted is accurate. That being said, we will not be able to handle streams that don't broadcast accurate metadata with our current methods. We aim to capture a highest possible quality audio data, within a reasonable size per song, and we have found that 96 kbps OGG works the best in terms of AI recognition rates later on.

Streamripper outputs a filename like this - "0001_ - 2PAC - Changes.ogg" - A number of the file in the current session, followed by an underscore and the name of the song, as streamed. I don't know what will happen when we stumble upon the same song on the same possition, producing the same file name, but it will either append a number, overwrite the old one, discard the new one or crash. I also don't know what will happen when we reach the record after 9999-th record. Streamripper has many cmd switches I haven't looked at, because I am not sure this is the software we want to be using in the long run.
<br>
<br>


## K2. Curation and Correction

`_cmdSongCurator.exe`  
`_cmdFileRename.exe`

After ripping streams, we will take the raw dumps, remove the leading numbers from the filenames and split them in folders by song names. We will also remove leading spaces and hyphens from the beginning of the song names, because, for some reason, our song names, at least from the stream we are working with, all start with spaces and hyphens. We might want to remove other characters in the future, as well, but we will see if we have such issues with other streams. We do that renaming automatically with a .Net CMD utility we have developed called `_cmdSongCurator.exe`.

Streamripper however seems to mangle non-ASCII unicode file names, so we keep a dictionary of messed names vs corrected names, and we run another CMD utility to fix the names - `_cmdFileRename.exe`. There are not a lot of those songs, but some do pop up here and there, so this is an important step.

Below is the folder structure of the folder containing the curated songs. The tracks directory contains one specimen of each song, and the variants directory contains all of the recordings in this curation job.

```
\radiowatch\K2. Curated stream dumps
└─\RADIO ENERGY
  ├─\tracks
  │ ├─\2 4 FAMILY - Stay.ogg
  │ └─\2 BROTHERS ON THE 4TH FLOOR - Come Take My Hand.ogg
  └─\variants
    ├─\2 4 FAMILY - Stay
    │ ├─\2 4 FAMILY - Stay.ogg
    │ └─\2 4 FAMILY - Stay(1).ogg
    └─\2 BROTHERS ON THE 4TH FLOOR - Come Take My Hand
      ├─\2 BROTHERS ON THE 4TH FLOOR - Come Take My Hand.ogg
      ├─\2 BROTHERS ON THE 4TH FLOOR - Come Take My Hand(1).ogg
      └─\2 BROTHERS ON THE 4TH FLOOR - Come Take My Hand(2).ogg
```
<br>
<br>

## K3. Spectrograms

`ffmpeg-full-pipeline.bat`  
`ffmpeg-short-pipeline.bat`

We create spectrograms of songs so that we can visually inspect the songs, and not have to listen to them to figure out if they are the same tracks, which would be error prone and tedious. We use ffmpeg to do that. A problem here, at least for machine recognition that we want to implement in the future, is that songs are of different length - some cut off earlier then others for example. We want to achieve the same time per pixel of graph value for different songs, otherwise we will get stretched and compressed spectrograms relative to one another. So we solve this by first pumping our songs to 10 minute length (with ffmpeg), creating the spectrograms (also with ffmpeg) and then removing the dark region of silence at the end (with magick image processing utility). 

All this happens within the `ffmpeg-full-pipeline.bat` and `ffmpeg-short-pipeline.bat` batch scripts we have deviced. The short version is for a small sample (one song) while the full version is a long few hour operation on all the curated songs.

Python script is also available in the tools folder that can be used to create the spectrograms instead of ffmpeg. Python spectrograms are pixelated and can possibly be beneficial for automated recognition, especially non-AI based one.
<br>
<br>


## K4. Canon

The Canon folder contains samples of each song, for future reference.

We manually inspect the spectrograms for each song, find the best looking ones (the longest, even by a small margin, like a second), listen to the songs in a player like VLC to see if there is too much of an interference - like radio host speech and theme melody at the start and at the end of the song, pick up the best looking track, and copy the audio file to the Canon folder. We also rename the files to have a normal name, and write an entry at `.canon.json` describing the song, its original streamed name(s) and the number of samples of that same song we have.
<br>
<br>


## K5. Recognized songs Json

`_cmdMusicIdentifier.exe`

We are using audio recognition AI AudD.io to recognize songs for us. We have developed the command line utility `_cmdMusicIdentifier.exe` to automate the task for us. AudD.io works with an api key and HTTP requests with a song, that returns a response json file with various attributes of the song - like urls on different platforms, artist, album, release year, etc. We collect those json files in `\K5. Recognized songs Json` folder, and consume them with our bots.

The recognition rate we have achieved is generally around the 85% mark with 96kbps .ogg files. This is for 90's hits - for local songs like Serbian turbo-folk, Bulgarian chalga or Roma kuchek meme tracks probably the recognition rates will be abysmal, but we just need to roll with it.
<br>
<br>


## K6. Confirmed songs Json

Later on, we go and manually inspect those AI recognized songs, or manually figure out and track down the unrecognized ones, using spectrograms in the process. We also confirm the data - Artists, years, etc. and the Links, giving us the final knowledge base - Samples of songs, Listing of names used for those songs on different stations and platforms, spectrograms of those songs, and detailed information about the songs.

The beauty of the spectrograms is that you don't need the original song itself any more, and spectrograms do not infringe on intellectual property as they cannot be used to fully recreate the original song.
<br>
<br>


## I1. Map
```
(Streamripper - streamripper-rip.bat) ->
  Raw stream dumps -> (_cmdSongCurator + _cmdFileRename) ->
    Curated stream dumps -> (ffmpeg-full-pipeline.bat) ->
      Spectrograms -> (manual inspection) (manual copying best fits) ->
        Canon;

Canon -> (_cmdMusicIdentifier) ->
  Recognised songs Json (manual inspection) ->
    Confirmed songs Json;
```
<br>
<br>

### Links
[Radiowatch](/listiary/radiowatch/)<br>
[Radiowatch - FAQ](/listiary/radiowatch/ifaq/)<br>
[Radiowatch - FAQ (Radio)](/listiary/radiowatch/rfaq/)<br>
[Radiowatch - Pipeline K](/listiary/radiowatch/pipeline-k/)<br>
[Radiowatch - Pipeline W](/listiary/radiowatch/pipeline-w/)<br>
<br>
[Project Listiary](/listiary/)<br>
[Project Describe](/language/)