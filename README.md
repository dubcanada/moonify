Updated Video.JS Moonify Skin
=======

This is a version of <http://jlofstedt.com/moonify/> that has been updated to the latest Video.JS version (3.2)

All credit goes to <http://jlofstedt.com/moonify/> for the original product.

### Installation Instructions ###

1. Download the above files as well as the latest video.js files.
2. Open up the example application and config it as per your liking (currently captions are not styled, nor are they turned off)
3. Add moo-css class to your div, keeping the vjs-default-skin (I know the guide says to remove it, but we just override it, we don't replace it)
4. Include the moo.css file in your html document after the video.js css file

So it will end up looking like

    <video class="video-js my-custom-skin vjs-default-skin" ...>
