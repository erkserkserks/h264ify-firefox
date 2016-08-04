<meta property="og:image"
    content="https://raw.githubusercontent.com/erkserkserks/h264ify-firefox/master/icons/icon128.png"/>

# h264ify-firefox

![](https://raw.githubusercontent.com/erkserkserks/h264ify-firefox/master/noncode/screenshot_video.png)

# About
h264ify is a Firefox/Chrome extension that makes YouTube stream H.264 videos instead of VP8/VP9 videos.

Try h264ify if YouTube videos stutter, take up too much CPU, eat battery life, or make your laptop hot.

By default, YouTube streams VP8/VP9 encoded video. However, this can cause problems with less powerful machines because VP8/VP9 is not typically hardware accelerated.

In contrast, H.264 is commonly hardware accelerated by GPUs, which usually means smoother video playback and reduced CPU usage.

# Requirements
Firefox

Looking for the Chrome version? See: https://github.com/erkserkserks/h264ify

# Installation
Install from here: https://addons.mozilla.org/firefox/addon/h264ify/

If all goes well, when you visit https://www.youtube.com/html5, you should see this:
![](https://raw.githubusercontent.com/erkserkserks/h264ify-firefox/master/noncode/screenshot_support.png)

Note: The current version of Firefox (35) doesn't support MSE, but when support arrives, h264ify will also block VP9.
