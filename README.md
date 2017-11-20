AdMob Cordova Plugin for Heyzap
==================================

This is a custom Apache Cordova plugin for AdMob/Google Mobile Ads to be used with the [Heyzap Cordova Plugin](github.com/Heyzap/heyzap-cordova). The plugin simply adds the AdMob sdk to both the iOS and Android platform projects in your Cordova project, along with the appropriate dependencies and permissions.

SDK Verisons
------------
- iOS: 7.18.0
- Android: Latest Google Play Services

Installing:
```
cordova plugin add https://github.com/Heyzap/heyzap-cordova-admob.git
```

Additional Steps:
You may need to disable bitcode in your Xcode project settings before building the app.
In the Xcode project explorer click on your app project, Go to the 'Build Settings' tab and change 'Enable Bitcode' to 'No' for all the dropdowns that aren't disabled.

Supported Platforms
-------------------
- iOS (cordova-ios engine 3.8.0 and later)
- Android (cordova-android engine 4.0.0 and later)

Documentation
-------------
Please visit our [documentation page](https://developers.heyzap.com/docs/cordova_sdk_setup_and_requirements#step-2-choose-your-3rdparty-sdks-optional) for guides on how to integrate heyzap with your Cordova app.
