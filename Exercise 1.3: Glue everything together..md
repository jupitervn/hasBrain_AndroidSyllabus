# Intent and intent filter
------

## Objectives:
* Learn how intent works, what is intent filter.
* Different between explicit intent and implicit intent.
* Task and backstack.

## Requirements:
* Use the existing source code from previous exercises.
* Write a new activity called SignUpStep3Activity with the following UI
![step3_ui.png](https://bitbucket.org/repo/AARp7y/images/2716911273-step3_ui.png)

* Press `DONE` button inside `SignUpStep2Activity` should bring user to `SignUpStep3Activity`
* Press `SEND EMAIL` button will open another app with email function(user can choose one if there are multiple apps that match this criteria) to send an email with this format:
    + To: {email}
    + Subject: User's registration info.
    + Content: 
```
{firstname}_{lastname}
{phone_number}
{salary} dollars
```
* Press `RESTART` should bring user back to `SignUpStep1Activity` for reentering the info.
* Press back hardward button on this screen should bring user back to `SignUpStep2Activity` with info that user has entered before.

## References:
* Tasks and backstack: http://developer.android.com/intl/zh-cn/guide/components/tasks-and-back-stack.html
* Intent and intent filters: http://developer.android.com/intl/zh-cn/guide/components/intents-filters.html
