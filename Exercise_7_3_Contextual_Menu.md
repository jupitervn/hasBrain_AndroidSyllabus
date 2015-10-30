## Objectives
* Learn how to provide users a contextual menu.

## Requirements
* Use the existing code from [Exercise 7.2](Exercise_7_2_Navigation_Drawer.md).
* Modify the layout to include a button to bookmark a post. You can choose your own way to store bookmarked posts.
> Colored star icon indicates that a post is bookmarked.

![Portrait post list](images/ex7/ex73/post_list_portrait.png)

![Landscape post list](images/ex7/ex73/post_list_land.png)

* Add the `Bookmark` menu to the navigation drawer.
![Portrait menu](images/ex7/ex73/bookmark_menu.png)

* Choose `Bookmark` menu will open a page that list all the bookmarked posts.
* Long press on an item inside `Bookmark` page will trigger the contextual menu like this:

![Portrait contextual Menu](images/ex7/ex73/selected_portrait.png)

![Landscape contextual Menu](images/ex7/ex73/selected_land.png)

* Tap on the `remove` icon will delete all the selected posts from bookmark.
* All the icons can be downloaded from here (this is the `xxxhdpi` you can resize for other screensizes if needed)
    + ![Bookmark](images/ex7/ex73/icons/por/ic_bookmark_star_unselected.png) ![Bookmark](images/ex7/ex73/icons/por/ic_bookmark_star_selected.png)![Bookmark](images/ex7/ex73/icons/land/ic_bookmark_star_unselected.png)![Bookmark](images/ex7/ex73/icons/land/ic_bookmark_star_selected.png)
    + ![Bookmark menu](images/ex7/ex73/icons/por/ic_folder_special.png)
    + ![Remove icon](images/ex7/ex73/icons/por/ic_remove_circle_24dp.png)

## References
* How to add a contextual menu: http://developer.android.com/guide/topics/ui/menus.html#context-menu

## Bonus:
* `Listview` already has a way to handle contextual menu for you, can you find out the way to do that?
* Find a way to make contextual Menu work with `Toolbar`.
