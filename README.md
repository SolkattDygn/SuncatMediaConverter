# SuncatMediaConverter
Converts video file audio codec to a video file with other codec
Mainly made to easy convert AAC codecs in video files to PCM
so the video files can be used in Davinci Resolve on Linux.

Some options are a little uggy but converting a video file from 
AAC codec to PCM (.wav) Should be working fine.

NOTE: What works for me might not work for you.
      Use at your own risk, make sure you educate yourself where needed.

HOWTO USE:
- Install FFmpeg (if not done already)
- Download script to the same location where you have the files 
  you want to convert.
- Run from Terminal (OR Double click the script and choose Run In Terminal)
- Choose the input file (.mkv / .mp4)
- Choose output
- Choose output format (usually the same as input)
- Choose output audio codec
- open up the newly created folder 'Converted'
- Find your converted file.

So for a .mkv file with a AAC codec that needs to be converted to a .mkv with PCM
its option; 2,2,2,1.

WHY?
Created a bash script on linux in order to facilitate a 
more enjoyable experience converting the audio codec in videofiles.
It can be done from terminal but this makes it easier in my opinion.

Originally created to convert videofiles (.mp4/.mkv) with AAC audio codec to 
a videofile with a PCM codec so it can be used in Davinci Resolve Studio
running on Linux.
