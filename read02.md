# HTML Structure
### 1- HTML pages are text documents.
### 2- HTML uses tags (characters that sit inside angled 
### brackets) to give the information they surround special 
### meaning.
### 3- Tags are often referred to as elements.
### 4- Tags usually come in pairs. The opening tag denotes 
### the start of a piece of content; the closing tag denotes 
### the end.
### 5- Opening tags can carry attributes, which tell us more 
### about the content of that element.
### 6- Attributes require a name and a value.
### 7- To learn HTML you need to know what tags are 
### available for you to use, what they do, and where they 
### can go


# Flash, Audio & Video
### 1- Flash allows you to add animations, video and audio to 
### the web.
### 2- Flash is not supported on iPhone or iPad.
### 3- HTML5 introduces new <video> and <audio>
### elements for adding video and audio to web pages, but 
### these are only supported in the latest browsers.
### 4- Browsers that support the HTML5 elements do not 
### all support the same video and audio formats, so you 
### need to supply your files in different formats to ensure 
### that everyone can see/hear them

### Exmple:
### <!DOCTYPE html>
### <html>
### <head>
 ### <title>Flash, Video and Audio</title>
 ### <script type="text/javascript" 
 ### src="http://ajax.googleapis.com/ajax/libs/
 ### swfobject/2.2/swfobject.js"></script>
 ### <script type="text/javascript">
 ### var flashvars = {};
 ### var params = {movie: "../video/puppy.flv"};
 ### swfobject.embedSWF("flash/osplayer.swf", "snow", 
 ### "400", "320", "8.0.0", flashvars, params);</script>
### </head>
### <body>
 ### <video poster="images/puppy.jpg" width="400" 
 ### height="320" controls="controls">
 ### <source src="video/puppy.mp4" type='video/mp4;
 ### codecs="avc1.42E01E, mp4a.40.2"' />
 ### <source src="video/puppy.webm" type='video/webm;
 ### codecs="vp8, vorbis"' />
 ### <div id="snow">
 ### <p>You cannot see this video of a puppy playing 
 ### in the snow because this browser does not 
 ### support our video formats.</p>
 ### </div>
 ### </video>
### </body>
### </html


