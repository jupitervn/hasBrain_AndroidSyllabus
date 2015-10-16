## Objectives:
* Learn how to display images inside an adapter view and how it's different from display image in normal view.
* Decode and scale image are very expensive operations. It should not be run on main thread.
* Learn how to write a simple image loader.

## Requirements:
* Image processing is a very expensive operation. It should not be run on main thread.
* 

## References:
* Processes, threads, async tasks: http://developer.android.com/guide/components/processes-and-threads.html
* How to display bitmaps on views https://developer.android.com/training/displaying-bitmaps/index.html
* Some libraries to display image:
    + Picasso: http://square.github.io/picasso/
    + Universal image loader: https://github.com/nostra13/Android-Universal-Image-Loader
    + Fresco: https://github.com/facebook/fresco
    + Glide: https://github.com/bumptech/glide