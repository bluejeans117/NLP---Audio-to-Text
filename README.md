# Audio to Text

This project takes an NLP approach to derive information from audio/video files. The following workflow and tools were used:

Workflow - Tool:

1) Download audio/video file - youtube_dl package
2) Audio to Text Conversion - speech recognition 
3) Text preprocessing - punctuator API
4) Sentiment Analysis - Vader
5) Extraction based Summarization - aylien api and pagerank algorithm 


The jupyter notebook is accompanied by a ppt that was used for class presentation purposes

Additional requirements to packages used in notebook.

- youtube_dl
-ffplay
-ffprobe
-ffmpeg


Source code for the punctuator api can be found here: https://github.com/ottokart/punctuator2

Better results can be generated when the youtube subtitle url is used as opposed the punctuator. 
