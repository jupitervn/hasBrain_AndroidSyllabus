## Objectives:
* Learn how to use shared preferences to store key/value data.
* Learn how to use `SwitchCompat`

## Requirements:
* Apply some more settings to your game at https://bitbucket.org/cdv1010/hasbrain_androiddocumentation/wiki/Exercise%203.2:%20How%20activities%20and%20fragments%20live%3F
* `SettingsActivity` can be accessed by pressing the top-right menu button.
* The UI should look like this:

![settings_layout_por.png](https://bitbucket.org/repo/AARp7y/images/1271928217-settings_layout_por.png)

* There are two options for this game:
    + Time limit: range from 5 sec to 60 sec. The value set here will affect the time of game afterwards. Default value is 10 sec.
    + Change the value of the seekbar should update the small textview below `Time Limit` label.
    + Record highscore: if it's enabled then after the one game is finished, the score is automatically recorded else it will be discarded. Default value is enabled.
    
* Every previous settings should be shown when user comes to this activity.

## References:
* How to use SharedPreferences: http://developer.android.com/training/basics/data-storage/shared-preferences.html
* How to use `SwitchCompat`: https://developer.android.com/reference/android/support/v7/widget/SwitchCompat.html