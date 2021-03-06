# SnackBar; toast-like alert pattern for Android inspired by the [Google Material Design Spec](http://www.google.com/design/spec/components/snackbars-and-toasts.html)

![Mr.Waffle](https://cloud.githubusercontent.com/assets/1573624/4054112/5f907220-2d88-11e4-9624-dd08fa49ac78.png)

# Features

* Set message text and optionally duration
* Shows only one message at a time 
* Can have action item (e.g. undo, refresh, etc.)
* Set text color of action items 
* Swipe down to dismiss all notifications as per documentation
* Backwards compatible to 2.3.x

![Snackbar Screenshot via Google](http://material-design.storage.googleapis.com/images/components-toasts-specs-spec_toast_03_1_large_mdpi.png)


[![Snackbar on Google Play](http://developer.android.com/images/brand/en_generic_rgb_wo_60.png)](https://play.google.com/store/apps/details?id=com.mrengineer13.snackbar.sample)

# Usage
##1. Adding Snacks to your project
###Android Studio/IntelliJ
1. Download ZIP then extract the SnackBar project
1. From IDE: File > Import Module -> SnackBar
1. File > Project Structure > Dependencies Tab > Add > Module dependency > SnackBar

###Eclipse
1. Download ZIP then extract the SnackBar project
1. From Eclipse menu: New > Android Project from Existing Code > SnackBar project > Finish
1. Right click on your project
1. Android > Library: Add > SnackBar
        
##2. Show a message

####Add Style to your activity
    <item name="snackBarContainerStyle">@style/SnackBar.Container</item>
    <item name="snackBarTextStyle">@style/SnackBar.Message</item>
    <item name="snackBarButtonStyle">@style/SnackBar.Button</item>

####Create SnackBar
    Snackbar mSnackBar = new SnackBar(this);
    mSnackBar.show("This library is awesome!");
    

[![SnackBar on Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-SnackBar-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/869) 