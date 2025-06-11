---
layout: page
title: Radiowatch - Pipeline W
permalink: /listiary/radiowatch/pipeline-w/
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


### W1. Stream Sources

The first step in tracking content on audio streams is figuring out where those streams are played - this is - the URLs of the streams. We can extract those from websites source codes - usually buried within JavaScript files, or we can just use the request monitor in our browser inspector to observe the requests that are being made by a web page. The later is often the easiest option. Plus, we get to observe if the site pulls something like a JSON metadata from some URL, which is often the case with icecast streams.
<br>
<br>

### W2. Playlist dumps

`cmdStreamGazer.exe`  
`cmdStagePoolUploader.exe`  

After identifying stream sources, we run our StreamGazer bot continuously, to keep collecting playlists for us. The bot keeps writing to text files the information, while "gazing" at multiple streams, and splitting/rolling the text files every 24 hours.

We periodically run the `cmdStagePoolUploader.exe` tool to, well, upload the collected playlists to our staging pool, and delete the older ones from our PC.
<br>
<br>

### W3. Describe sources

Here, we have all the Describe source codes for our Radiowatch wiki. 
What we will do is have a bot that will download the data files from the staging pool, verify them against one another and against uploading user's reputation and curate them in the final articles, and add them in the appropriate folder, here.

We can use the database for this, but in the test version we use local storage. 
<br>
<br>

### W4. Compiled Json files

As we are using local files to test, we run the Describe compiler, targeting JSON output, and we store this output here.
<br>
<br>

### W5. Website

We have a local copy of the "Listiary" wiki here, that we use for testing. It is almost the same as the original, but some files are `.html` instead of `.php`, some functionality is omitted, and we have a plugin that allows us to load local JSON files for source data.
<br>
<br>


### Links
[Radiowatch](/listiary/radiowatch/)<br>
[Radiowatch - FAQ](/listiary/radiowatch/ifaq/)<br>
[Radiowatch - FAQ (Radio)](/listiary/radiowatch/rfaq/)<br>
[Radiowatch - Pipeline K](/listiary/radiowatch/pipeline-k/)<br>
[Radiowatch - Repo Map](/listiary/radiowatch/repo-map/)<br>
<br>
[Project Listiary](/listiary/)<br>
[Project Describe](/language/)