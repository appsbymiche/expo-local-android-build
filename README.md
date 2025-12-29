# expo-local-android-build
How to build an expo android project locally
Methods for Local Android Builds
There are two primary approaches for building an independent Android app locally with Expo: using the Expo CLI's run:android command or using the eas build --local command. 
Method 1: Using npx expo run:android (Recommended for development/debugging) 

1. run 'npx expo prebuild'

2a. To buld an apk that depends on your local expo server use "npx expo run:android"

2b. To build a full apk use "npx expo run:android --variant release"
