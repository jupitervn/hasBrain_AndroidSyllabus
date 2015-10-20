## Objectives:
* Learn how the lifecycle of fragment and activity works.
* Learn how to handle configuration change(rotation, keyboard hidden...)

## Requirements:
* Implements a simple game that counts how many times a person can tap in 10sec.
* Checkout the skeleton code at: [https://github.com/jupitervn/Android_HowFastAreYou](https://github.com/jupitervn/Android_HowFastAreYou)
* The UI should look like these below screenshots:

Default portrait layout

![default_layout_por.png](https://bitbucket.org/repo/AARp7y/images/1821454335-default_layout_por.png)

Default landscape layout

![default_layout_land.png](https://bitbucket.org/repo/AARp7y/images/1386731440-default_layout_land.png)

Gaming portrait layout

![gaming_layout_por.png](https://bitbucket.org/repo/AARp7y/images/845729877-gaming_layout_por.png)

Gaming landscape layout

![gaming_layout_land.png](https://bitbucket.org/repo/AARp7y/images/2663761400-gaming_layout_land.png)


* The UI contains 2 parts: game part and the high score part.
* The count should be updated when user presses `TAP` button.
* `TAP` button should be disabled until user presses `START`.
* After press `START`, `START` button is disabled while `TAP` button is enabled.
* After 10sec, the `TAP` button will be disabled and the result will be updated in the high score panel.
* The highscore panel should be implemented inside `TapCountResultFragment` a fragment.
* If user rotates the phone(or press `HOME`):
    + While a game is playing (clock is ticking) then that game should be paused and `START` button becomes `RESUME` button. After user presses `RESUME`, the game will continue.
    + If a game has stopped then the last tap count should be preserved.

* Highscore list must be preserved even if user rotates the phone (or presses `HOME`).

## References:
* Activity lifecycle: http://developer.android.com/reference/android/app/Activity.html
* Fragment lifecycle: http://developer.android.com/reference/android/app/Fragment.html
* Complete diagram of activity and fragment lifecycle https://github.com/xxv/android-lifecycle
* How to handle configuration change: http://developer.android.com/guide/topics/resources/runtime-changes.html
* Comunicate between activity and fragment: http://developer.android.com/training/basics/fragments/communicating.html

## Bonus:
* Log all activities and fragments lifecycle event to see how everything works.
* What is `setRetainInstance()` and how does it affect the fragment lifecycle.