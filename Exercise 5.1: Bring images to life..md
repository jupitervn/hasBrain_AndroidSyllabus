## Objectives:
* Learn how to work with camera and bitmap.
* Learn how to use `ImageView` to display an image.

## Requirements:
* Use your old code from **Exercise 1 or 3**
* Add function for user to take a picture to be used as his avatar.
* Change the previous layout of step 1:

![user_sign_up_avatar.png](https://bitbucket.org/repo/AARp7y/images/3430005683-user_sign_up_avatar.png)


* The dummy profile picture should be gotten from this url: http://mindsparx.in/wp-content/uploads/2013/07/Dummy-Profile-Picture.jpg
* Press the dummy profile picture will open camera app to take picture.
* After the picture is taken, display it inside the `ImageView`
* If user doesn't take a picture as his avatar then show a Toast with this message `You must choose an avatar`.
* Send the image as an attachment when user press `SEND EMAIL` in step 3. The image to be sent using email should only have the maximum dimension(width or height) of 400px.

## References:
* How to work with camera: http://developer.android.com/training/camera/photobasics.html
    + Please notice the way to scale an bitmap efficiently. 
* Toast: http://developer.android.com/guide/topics/ui/notifiers/toasts.html





