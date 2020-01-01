# html5-video-element-onpage-buffering-tracks
HTML5 video player code 2019

Add your own video to your website without any branding or restrictions that an embeded YouTube or Vimeo video might require.	

How it works... you will need two versions of your video as mp4 and ogv on your server (or linked to an approved resource location). Not all web browsers support the HTML5 video tag with mp4, yet. If a browser does not support mp4, it will skip to the next resource and play the ogv file. Most browsers will either support mp4 or ovg, if you want to make sure you include all browsers, you can add webm too. You can change the title, but instead of displaying the title, this code improves the interface and user experience since the down-click will pause/play the video. Everything else works in the browser with HTML5.

In the code...

Poster: a png file as your video still screenshot.
Width: The width of the video on your webpage.
Mp4, webm, ogv: video files with mixed support for major web browsers.
Track: add a vtt file format to include subtitles for your video. Read more about HTML5 video tracks.
Last line: Fallback text if users are not using a modern browser to warn them that thier browser does not support HTML5 video.
