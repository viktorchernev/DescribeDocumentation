---
layout: page
title: Radiowatch - Repo map
permalink: /listiary/radiowatch/repo-map/
exclude: true
---
<br><br>
### 1. Backup

`/.backup`  

The backup folder contains archived backup copies of the project, as well as a local copy of the Github repository that we host our tools for the project in - `/.backup/.github`.
Most of the archives are password-protected, as their contents are not open-source (at least yet). The archives are partial, containing the most important and easy to backup data - the software we have created and some of the tooling.

But the project is large - both in size, especially our spectrograms database, and in terms of the number of files some of the third party tools contain - making it hard to archive and cumbersome to upload. So, we are backing the project on local storage media, and uploading to GitHub only our tools.
<br>
<br>

### 2. Compiler

`/.compiler`

This folder contains a copy of the Describe compiler CLI, that is used for compiling describe files for the project.
<br>
<br>


### 3. Tools

`/.tools`

Here we have most of the tooling for our project, along with some batch scripts we have developed.

`cmdStagePoolUploader` - Cmd App to upload data to our staging pool.<br>
`cmdWaveGazer` - Our StreamGazer bot that collects data (need to rename the folder).<br>
`DontSleep` - A useful portable GUI utility that prevents Windows from sleeping. [Download](https://dont-sleep.en.softonic.com/)<br>
`ffmpeg` - A suite of utilities for audio manipulation we use to create spectrograms. [Download from Github](https://github.com/FFmpeg/FFmpeg)<br>
`image-magick` - A command line image manipulation utility, we use to crop our spectrograms. [Download](https://imagemagick.org/script/download.php)<br>
`py-spectrograms` - Few scripts we developed for doing what we do with ffmpeg, but in python.<br>
`StagingPool` - Our php/html staging pool software.<br>
`Streamripper` - A command line tool for recording songs off radio streams. [Download fr Github](https://github.com/streamripper/streamripper)<br>
Also, a number of batch files that automate the tasks we perform with these tools.
<br>
<br>

### 4. Tools - Visual Studio

`/.tools-vs`

Here we have the rest of the tooling for our project - those are the tools we have developed ourselves.

`_cmdFileRename` - Rename files to fix mistakes in the names.<br>
`_cmdJsonToDs` - Get Audd.io JSON responses and turn them to a Describe source codes data base.<br>
`_cmdMusicIdentifier` - Use Audd.io to identify music tracks.<br>
`_cmdSongCurator` - Curate downloaded tracks with Streamripper.<br>
`cmdStagePoolUploader` - The stage pool uploader utility.<br>
`cmdStreamGazer` - Our song title collecting agent.<br>
`guiPOC1` - An old app, but containing useful classes.<br>
`guiPOC2` - Useless old app.
<br>
<br>

### 5. Work

`/.work`

The work folder contains old work files, and sometimes current work files. In this repository, where the work is done in the repository folders directly, the work folder serves more as a backup than anything else - back up of work in progress, without the need for a github commit, backup of work that could be needed later on. etc.
<br>
<br>


### 6. The K pipeline 

See [pipeline-k article](/listiary/radiowatch/pipeline-k/) for more details - Serves for acquiring knowledge about various songs.

`K1. Stream dumps` - The raw content we get from Streamripper.<br>
`K2. Curated stream dumps` - Same dumps, but renamed properly, and sorted into folders.<br>
`K3. Spectrograms` - The spectrograms made from those curated dumps.<br>
`K4. Canon` - Manually identified song best samples - we find the best sample we have, and put it here.<br>
`K5. Recognized songs Json` - Songs we have recognized with AI. Contains JSON response files.<br>
`K6. Confirmed songs Json` - Manually confirmed AI recognitions.
<br>
<br>


### 7. The W pipeline 
See [pipeline-w article](/listiary/radiowatch/pipeline-w/) for more details - Serves for tracking various song titles that are being played.

`W1. Stream Sources` - Files containing different stream URLs - of big stations.<br>
`W2. Playlist dumps` - The now-playing songs data title we are after - that we get with StreamGazer.<br>
`W3. Describe sources` - All the Describe source files for our Listiary Wiki - Radiowatch.<br>
`W4. Compiled Json files` - The compiled Describe sources.<br>
`W5. Website` - The Radiowatch wiki website we are building - a local copy.
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