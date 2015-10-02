# SIMPLE CALCULATOR
## Description:
Implement a simple calculator of positive numbers that has this UI:
![layout.png](https://bitbucket.org/repo/AARp7y/images/3958247525-layout.png)

![layout_land.png](https://bitbucket.org/repo/AARp7y/images/3076057699-layout_land.png)


## UI requirements:
+ Two textviews should have these ids: `@+id/tv_formula`(formula textview), `@+id/tv_result` (result textview)
+ Text inside these two textviews will alight right.
+ Formula textview should have textcolor: **#757575** in portrait and **#b61414** in landscape
+ Result textview should have textcolor: **#939393** in portrait and **#b7339** in landscape
+ Background of left-sided buttons: **#434343**, when pressed: **#636363**
+ Background of right-sided buttons: **#636363**, when pressed: **#838383**
+ While on landscape: right-sided buttons’ min width is 360px in xhdpi phone screen and 150px in hdpi phone screen.
+ `*` and `/` will have higher priority than `+` and `-`
+ DEL button will clear one right-most character off the current expression.
+ If device’s orientation is changed, the current formula and result should be kept.
+ Result is calculated when user presses `=` button.
+ Pressing = will move the result from result textview to formula textview and clear result textview.
+ Show a dialog with this text “Your expression cannot be calculated” if user presses “=” on an invalid expression.


## Bonus:
+ Result is calculated on the fly while user inputs operands and operators.
+ Supports negative numbers.
+ Supports more operators if you want.
