## Android Tools:

1. SDK tools
2. Build tools
3. Platform tools
4. Android Emulator


### 1. SDK tools: 
These tools can be found in "<your_android_sdk>/tools/bin/" folder.These tools does not depend on the android platform or the android version you are developing on and are the essential tools required for the android development.Few of the major tools are as follows:

**1. apkanalyzer** used to analyze the apk, it's size and files inside the packaged entity.This is a pretty helpful tool to check the contribution of different components to the overall download size of apk.

**2. avdmanager** used to create/update the AVD (Android virutal device).These devices can be used for testing your apks.

**3. lint** used for static analysis of code.It helps to identify and correct problems with the structural quality of the code.

**4. sdkmanager** used to get the information about the packages installed for the android sdk.This is also used to update, install or uninstall the android sdk packages.


### 2. Build tools: 
These tools can be found in "<your_android_sdk>/build-tools/<version>/" folder.These tools are used to compile,debug or test your application.For each API level there is new build tool version(started from API level 18).Like API level 23 has build tool versions 23.0.X i.e. 23.0.0,23.0.1,23.0.2 and 23.0.3.
  
 **1. aapt** stands for Android asset packaging tool. Android Studio and Android Gradle Plugin use it to compile and package your app’s resources. It parses, indexes, and compiles the resources into a binary format that is optimized for the Android platform.
 
 **2. apksigner** is used to sign the apk.You can get more details about apk signing [here](www.google.com).
 
 **3. zipalign** is used to align the data into a archive file i.e. APK in android.This helps to optimize the APK to take less memory.More details about the process is [here](www.google.com).
              
### 3. Platform tools: 
These tools can be found in "<your_android_sdk>/platform-tools/" folder.As the name signifies these tools are updated for every new version of android platform to support new features.Few of the major tools are as follows:

**1. adb** stands for Android debug bridge. This tool helps you to connect with a android device or emulator and to perform various actions like installing or debugging an apk.There are three parts of this tool
- A **client**, which sends commands. The client runs on your development machine. You can invoke a client from a command-line terminal by issuing an adb command.
- A **daemon (adbd)**, which runs commands on a device. The daemon runs as a background process on each device.
- A **server**, which manages communication between the client and the daemon. The server runs as a background process on your development machine.

**2. logcat** is used to view logs of the device attached.You can also add filters to view logs for an specific app.


### 4. Emulator:
These tools can be found in "<your_android_sdk>/emulator/" folder.These tools provides the functionality to use the android emulator and manage them.

**1. emulator** is used to start an emulator.An emulator is a device-emulation tool that you can use to debug and test your applications in an actual Android run-time environment.

**2. mksdcard** is used to create a virtual external sd card for the emulator.

> Please note that AVD and emulator are two different things. An Android Virtual Device (AVD) is an emulator configuration that defines the hardware and software options to be emulated by an Android Emulator.





