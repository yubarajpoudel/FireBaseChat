

Simple Firebase chat application
-------------
Clone this project and follow the following steps for firebase setup.
> To cone from the github, open terminal and execute following command
> *git clone git@github.com:yuviii/FireBaseChat.git*

FireBase application to make the chat application.

> **What you can do with the Firebase**
 1. Allow users to sign in. Sync data using the Firebase Realtime
 2. Database. Receive background messages with Firebase Notifications.
 3. Configure an application with Firebase Remote Config. Track
 4. application usage flows with Firebase Analytics. Allow users to send
 5.  Display ads with AdMob.
 6.  Report crashes with Firebase Crash Reporting. Test your app with
 7.  Firebase Test Lab.
 
 **Set up android project in your firebase**
 
 ![firebase create](https://github.com/yuviii/FireBaseChat/blob/master/chat/chat1.png?raw=true)
> 
 Add your project package name, in my project for
	 *com.yuvi.chatapplication*
Add your shar-1 certificate 
to have your certificate open the terminal in android studio and run the following command.
*keytool -exportcert -alias androiddebugkey -keystore ~/.android/debug.keystore -list -v -storepass android*

after the that click on add app, and the browser will download the google-sevices.json file.just paste this file on your app folder.

 ![firebase create](https://github.com/yuviii/FireBaseChat/blob/master/chat/chat2.png?raw=true)

now you are almost done
> **copy this in your project level build.gradle file**
 *classpath 'com.google.gms:google-services:3.0.0'*
 **copy this in app level build,gradle file**
 apply plugin: 'com.google.gms.google-services'
 
Here it is now you can use chat application on your own firebase server enjoy. Your ouput will be like this.
![Final output](https://github.com/yuviii/FireBaseChat/blob/master/chat/output.gif?raw=true)