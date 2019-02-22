  

# :iphone: Workflow React-Native

  

## :computer: Windows
Using windows as an operating system is only possible for Android

## :alien: Android

Configuring the development environment for the React-Native framework

 - Nodejs
 - Python 2
 - JDK
 - Android Studio

---
**:package: Package Manager**

With administrator permission, enable PowerShell to install the libs. To do this simply enter the following codes:

> PowerShell.exe

`Get-ExecutionPolicy`

If return *restricted*

    Set-ExecutionPolicy AllSigned
  Else
  

    https://gist.githubusercontent.com/diego3g/40a67dd23a0b412f2fd5771ff6fd9cc6/raw/3086e8082ee6c88471b7c27fc3baf9073cb72766/chocolatey2.sh
---
For install **Chocolatey Package Manager** just copy the cmd and paste at cmd.exe 

> cmd.exe

   `https://gist.githubusercontent.com/diego3g/7596b2d4faa49adb3e4d3c24ef0504d2/raw/68379a5cff446da972f4ce501d93fbd9ed04feb0/gistfile1.txt`

Check if chocolatey are installed

    choco
---

**Install Dependencies**

    choco install -y nodejs.install python2 jdk8

For install global **React-Native**:

    npm install -g react-native-cli
---

**Android Studio**
You will need to download [**Android Studio**](https://developer.android.com/studio/index.html) to emulate an Android Device.

- Android SDK
- Android SDK Platform
-  Performance (Intel ® HAXM) 
-  Android Virtual Device

After installing Android Studio just set up in the SDK Manager with which API you will work

**Set a variable ANDROID_HOME**

> *Appearance & Behavior > System Settings > Android SDK*
> Copy Android SDK Location

Go to system windows, click in *advance config systems*, and *choice variables*. Click in *add a new variable* and set:

    Variable Name: ANDROID_HOME 
    Variable Value: copy sdk manager path

After that its just create your project with react-native

    react-native init newProject

For run your app

    react-native run-android
 Logs
 

    react-native log-android

If you have some question just [check here](https://facebook.github.io/react-native/docs/getting-started)
