=== cordova-commpn implementation for Android Studio ===

This is to be used with plugman and the studio_tools branch of CordovaLib.

This allows for plugman to install plugins on an Android Studio project
containing a WebView.  This is useful for the use case where a user may want to
use Cordova with a default Android Studio project.  As usual, this code is licenced
Apache and the licence is attached.

How to use this code:

1. Copy the cordova directory to the root of your Android Studio project
2. Make sure you've linked the modified cordova-lib and plugman as per the  
contributor documentation found in cordova-lib
3.Run plugman in the directory like a regular platform project.

This is a proof-of-concept designed to allow better hybrid application use, this
is not meant to be used for production.
