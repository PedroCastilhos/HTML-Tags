**The controls attribute adds video controls, like play, pause, and volume.**

It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.

<hr>

HTML `<video>` Autoplay
To start a video automatically, use the autoplay attribute:

Example

```<video width="320" height="240" autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

Add `muted` after `autoplay` to let your video start playing automatically (but muted):

For audio files are the same attributes.
