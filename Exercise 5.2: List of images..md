## Objectives:
* Learn how to display images inside an adapter view and how it's different from display image in normal view.
* Decode and scale image are very expensive operations. It should not be run on main thread.
* Learn how to write a simple image loader that can process the image off UI thread.

## Requirements:
* Check out skeleton code at:
* The project contains a list of car images which have size of 1280x960px.
* Display a list of cars to user with has the UI like below:

![carlist.png](https://bitbucket.org/repo/AARp7y/images/2707954630-carlist.png)

* Implements `ImageLoader` interface to read bitmaps from `raw` folder, scale them and display them in a list.

## References:
* Processes, threads, async tasks: http://developer.android.com/guide/components/processes-and-threads.html
* How to display bitmaps on views https://developer.android.com/training/displaying-bitmaps/index.html
* Some libraries to display image:
    + Picasso: http://square.github.io/picasso/
    + Universal image loader: https://github.com/nostra13/Android-Universal-Image-Loader
    + Fresco: https://github.com/facebook/fresco
    + Glide: https://github.com/bumptech/glide

## Bonus:
* Check if you can improve the performance by caching the images in memory.
* Use some of the libraries above to display images. Learn how to config them.