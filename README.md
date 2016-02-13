# AudioSpectrum
A real-time spectrum visualizer for audio files, written in Gambas.

This little program takes an audio file, plays it and uses the GStreamer "spectrum" element to get a full, realtime spectrum from the stream.
It then applies a few aesthetic algorithms to the spectrum (logarithmic scaling of the X axis, and exponential smoothing of the result), for it to be finally rendered using OpenGL.

![](http://pix.toile-libre.org/upload/original/1432859404.png)

This program requires GStreamer (gstreamer-good-plugins), Gambas 3.8 (revision #7082 at least), as well as the following Gambas components (and their dependencies) :

- gb.gui
- gb.gui.opengl
- gb.form
- gb.media
- gb.opengl
- gb.opengl.glu

[Gambas Website](http://gambas.sourceforge.net)

[GStreamer Website](http://gstreamer.freedesktop.org)

[OpenGL Website](https://www.opengl.org/)
