# ## Configure Qt Creator for Android Development ##

## Prerequisites: 
* QtCreator(Open Source or Lincensed)
* Android Studio
* JDK(Java Development Kit) 

## Steps 

* Open Qt Creator.
* Go to Edit -> Preferences.
* Click on Android in the Preferences window.
* Ensure that to install [Android Studio](https://developer.android.com/studio).
* Install [JDK 18.0.2](https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html).
* Provide the proper file paths for JDK and Android SDK in Qt Creator settings.
* Click on Setup SDK. Verify that all the required components are installed (indicated by green ticks).
* Open the SDK Manager and select the desired Android version(s) for your development needs.
* Go to Devices and add an Android device. If it doesn't appear, close and reopen Qt Creator.
* After adding the device, refresh and start the Android Virtual Device (AVD).
* Now you can run your code in the virtual machine.

