VitamioMediaPlayerDemo
=====================

VitamioMediaPlayerDemo is an standalone Android library designed to facilitate use Vitamio. Please reference this as Android library when you used.

![Screenshot](https://raw.githubusercontent.com/yixia/VitamioMediaPlayerDemo/master/vitamio_screenshot.png)

How to use?
==========

1. Import Android library [VitamioBundle](https://github.com/yixia/VitamioBundle).
2. Import Android library [ZI](https://github.com/yixia/ZI).
3. Copy Activity description and permissions to your own project.
4. Invoke Vitamio to playback video.

```
    Uri uri = Uri.parse("xxxx");
    VideoActivity.openVideo(this, uri, "video title");
```

