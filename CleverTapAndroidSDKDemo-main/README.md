CleverTapAndroidSDKDemo
An Android application integrated with the CleverTap Android SDK as part of an assignment. The project demonstrates various CleverTap SDK features including event tracking, user profile updates, and push notifications.

Features Implemented
The application includes the following features as per the assignment requirements:

CleverTap SDK Integration: The CleverTap Android SDK is integrated into the project.
Debugger Enabled: CleverTap's debugger is enabled to view logs in Android Studio's Logcat using `CleverTapAPI.setDebugLevel(CleverTapAPI.LogLevel.DEBUG);.
"Product Viewed" Event: An event "Product Viewed" is automatically raised when the application launches.
User Profile Input:
Input fields for the user's Name and Email.
A "LOGIN" button that, upon clicking, passes the user's name and email ID to CleverTap using the onUserLogin function of the CleverTap SDK.
Custom Event Button:
A button that raises a custom event named "TEST" when clicked.
Push Notifications:
Setup for receiving Push Notifications via Firebase Cloud Messaging (FCM) integrated with CleverTap.
Requires google-services.json from a Firebase project configured for the app's package name (com.shailesha.clevertapandroidsdkdemo).
Project Setup
Clone the repository:
git clone [https://github.com/officialABHI1/CleverTapAndroidSDKDemo.git](https://github.com/officialABHI1/CleverTapAndroidSDKDemo.git)
Open in Android Studio: Open the cloned project in Android Studio.
Firebase Configuration:
The project includes a google-services.json file in the app/ directory, which is necessary for Firebase services, including Push Notifications. If you intend to use your own Firebase project, replace this file with the one from your Firebase project settings.
CleverTap Credentials:
The CleverTap Account ID and Token are hardcoded in the AndroidManifest.xml file as per the assignment.
Building and Running the Application
Sync Gradle: Once the project is open in Android Studio, allow Gradle to sync and download necessary dependencies.
Build APK:
To build a debug APK, navigate to Build > Build Bundle(s) / APK(s) > Build APK(s) in Android Studio.
The APK will be located in app/build/outputs/apk/debug/app-debug.apk.
Run on Emulator/Device:
Select an emulator or connect a physical device.
Click the "Run 'app'" button (green play icon) in Android Studio.
Documentation Referenced
CleverTap Android Quickstart Guide: https://developer.clevertap.com/docs/android-quickstart-guide
CleverTap Android SDK: https://developer.clevertap.com/docs/android
CleverTap User Profiles: https://developer.clevertap.com/docs/concepts-user-profiles 
CleverTap Android Push Notifications: https://developer.clevertap.com/docs/android-push 
