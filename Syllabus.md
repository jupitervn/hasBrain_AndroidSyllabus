# Android Syllabus
## Java and OOP
1. Java Programming:
    1. Basic: 
<http://www.ntu.edu.sg/home/ehchua/programming/java/J2_Basics.html>
    2. Variable types, autoboxing: https://docs.oracle.com/javase/tutorial/java/data/index.html
2. OOP
    1. OOP Basic:
        * http://www.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html
        * https://newcircle.com/bookshelf/java_fundamentals_tutorial/object_oriented
    2. Encapsulation, inheritance and polymorphism:
        http://www.ntu.edu.sg/home/ehchua/programming/java/J3b_OOPInheritancePolymorphism.html
    3. Java collections: List/Set/Map/Queue: <https://docs.oracle.com/javase/tutorial/collections/>
    4. Generic: https://docs.oracle.com/javase/tutorial/java/generics/
## Basic Android
1. Setup Environment
    1. Android SDK: https://developer.android.com/intl/zh-cn/sdk/index.html
    2. AndroidStudio: http://code.tutsplus.com/tutorials/getting-started-with-android-studio--mobile-22958
    3. How to use Android Studio: writing and debugging code
        * http://code.tutsplus.com/tutorials/getting-started-with-android-studio--mobile-22958
        * https://developer.android.com/intl/zh-cn/tools/debugging/index.html
        * https://developer.android.com/intl/zh-cn/sdk/installing/studio-tips.html
    4. Basic Gradle configs: Should know how to config a basic Android application: minSDK, compileSDK, packageName, dependencies http://tools.android.com/tech-docs/new-build-system/user-guide
2. App fundamentals and manifest file
    1. Should know 4 type of app components. http://developer.android.com/intl/zh-cn/guide/components/fundamentals.html
    2. Should know what is manifest file and which can be configured inside that file. http://developer.android.com/intl/zh-cn/guide/topics/manifest/manifest-intro.html
3. Activities, fragments and their lifecycles.
    1. Activity: How to start an activity? What can be configured for Activity inside Manifest file. http://developer.android.com/intl/zh-cn/guide/components/activities.html
    2. Fragment: Purpose of fragment? How to add a fragment? setRetainInstance()? http://developer.android.com/intl/zh-cn/guide/components/fragments.html
    3. Lifecycle of these components when configuration changes or app gets killed by system? https://github.com/xxv/android-lifecycle
4. UI controls: Button, EditText, TextView, SeekBar, CheckBox, AutocompleteTextView...
Learn about Android input controls: http://developer.android.com/intl/zh-cn/guide/topics/ui/controls.html
Should know some common attributes and listeners of each control
5. Intent and intent filters: What is intent, kind of intent, intent filter and intent matching http://developer.android.com/intl/zh-cn/guide/components/intents-filters.html
6. Basic layouts: FrameLayout, LinearLayout, RelativeLayout
    1. Main layouts of Android http://developer.android.com/intl/zh-cn/guide/topics/ui/declaring-layout.html
    2. Additional layouts: GridLayout, PercentageLayout 
        * http://developer.android.com/intl/zh-cn/reference/android/widget/GridLayout.html
        * https://developer.android.com/intl/zh-cn/reference/android/support/percent/PercentFrameLayout.html
    3. Layout performance and optimization http://developer.android.com/intl/zh-cn/training/improving-layouts/optimizing-layout.html
7. Access resources and builds app that supports multiple devices: http://developer.android.com/intl/zh-cn/guide/topics/resources/index.html 
    1. How to support multiple devices with different screen sizes.
    2. How to supports multiple languages
Listview/ExpandableListView/GridView/Recylerview and recycle mechanism
ListView: http://www.vogella.com/tutorials/AndroidListView/article.html 
GridView: http://www.tutorialspoint.com/android/android_grid_view.htm
ExpandableListView: http://javapapers.com/android/android-expandable-listview/
RecyclerView: http://code.tutsplus.com/tutorials/getting-started-with-recyclerview-and-cardview-on-android--cms-23465
Recycle mechanism, view holder pattern: http://lucasr.org/2012/04/05/performance-tips-for-androids-listview/
GridLayout, ViewPager/TabLayout
ViewPager: http://code.tutsplus.com/tutorials/android-user-interface-design-horizontal-view-paging--mobile-8231
TabLayout: https://guides.codepath.com/android/Google-Play-Style-Tabs-using-TabLayout
GridLayout: http://android-developers.blogspot.com/2011/11/new-layout-widgets-space-and-gridlayout.html
Dialogs/Toasts/Notification
Dialogs: dialog and dialog fragment http://developer.android.com/intl/zh-cn/guide/topics/ui/dialogs.html
Notification: http://developer.android.com/intl/zh-cn/guide/topics/ui/notifiers/notifications.html
Toasts: http://developer.android.com/intl/zh-cn/guide/topics/ui/notifiers/toasts.html
Menus/ActionBar/Toolbar
Menus: http://developer.android.com/intl/zh-cn/guide/topics/ui/menus.html
ActionBar: http://developer.android.com/intl/zh-cn/guide/topics/ui/actionbar.html
Toolbar: https://developer.android.com/intl/zh-cn/reference/android/widget/Toolbar.htm
Styles/Themes:
General styles and themes: should know how to use styles, themes http://developer.android.com/intl/zh-cn/guide/topics/ui/themes.html
Appcompat themes and material design: https://chris.banes.me/2014/10/17/appcompat-v21/
Simple data storage: file/shared preferences/sqlite
File, shared preferences: http://developer.android.com/intl/zh-cn/training/basics/data-storage/shared-preferences.html http://developer.android.com/intl/zh-cn/training/basics/data-storage/files.html
Sqlite: http://developer.android.com/intl/zh-cn/training/basics/data-storage/databases.html
Material designs app compat library: FloatingActionButton, SnackBar, CoordinatorLayout, AppBarLayout, NavigationDrawer
http://android-developers.blogspot.com/2015/05/android-design-support-library.html
http://hmkcode.com/material-design-app-android-design-support-library-appcompat/
http://android-developers.blogspot.com/2014/10/appcompat-v21-material-design-for-pre.html
Network communication
Synchronous vs Asynchronous: http://www.javatpoint.com/understanding-synchronous-vs-asynchronous
Basic about HTTP: http://www.tutorialspoint.com/http/index.htm
AsyncTask: http://developer.android.com/intl/zh-cn/training/basics/network-ops/index.html
Loader:   http://developer.android.com/intl/zh-cn/guide/components/loaders.html
Network libraries: Volley, Retrofit…: http://developer.android.com/intl/zh-cn/training/volley/index.html https://guides.codepath.com/android/Consuming-APIs-with-Retrofit
Questions: how to handle long running task? how to handle configuration changed while a request is processing?
Location and sensors: http://developer.android.com/intl/zh-cn/guide/topics/sensors/index.html
GPS and maps: http://developer.android.com/intl/zh-cn/training/location/index.html
Other sensors: 	
How to sign your app/ upload to Playstore: https://developer.android.com/intl/zh-cn/tools/publishing/publishing_overview.html
Intermediates Android
Animations
Touch event handling
How to write a custom view.
Improve layout performances
Camera
Video/Audio player
PendingIntent/AlarmManager
Services
Content provider
Concurrency programming
App permissions.
Google play services: GCM, App Invites, Place API, Analytics…
Basic testing technique: unit test/UI test.
Advanced Android
AppWidget
NFC/Bluetooth
SyncAdapter
AccountManager
Additional libraries to help while developing.
Proguard
Android data binding.
Dependency injection
Reactive Java/Android
Android Wear/Android TV/Android Auto
Bonus
Some architecture to care about: MVP, MVVM…
More gradle configurations
Continuous integration/delivery
References:
https://developer.android.com/intl/zh-cn/training/index.html
https://guides.codepath.com/android



