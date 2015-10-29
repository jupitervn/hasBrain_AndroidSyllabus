## Objectives:
* Learn how to add navigation drawer feature to your app.

## Requirements:
* Change the layout from tabs in [Exercise 6.2](Exercise_6_2_Tab_not_tap.md) to use navigation drawer.
* Create a new activity named `NavigationDrawerPostActivity`.
* Create a navigation drawer that shows a list of topics so user can navigate easily:

![Normal Navigation view](images/ex7/ex71/navigation_default.png)

![Navigation Drawer open](images/ex7/ex71/navigation_open.png)

![Navigation Drawer land](images/ex7/ex71/navigation_land.png)
* The navigation drawer will contain a header that shows the text `Reddit Post`
* The `hamgurger` icon should be changed to back arrow icon if the drawer is opened.
* Select one of the items inside navigation drawer will change the main content to show posts of the corresponding topic.
* Notice how a menu item is changed if it's selected.
* The navigation item icon can be downloaded from here: ![Icon](images/ex7/ex71/ic_menu_item.png)

## References:
* How to use `DrawerLayout` and `NavigationView`: https://guides.codepath.com/android/Fragment-Navigation-Drawer

## Bonus:
* See if you can show the navigation drawer that covers the actionbar like this:
![Bonus navigation drawer](images/ex7/ex71/navigation_above.png)
