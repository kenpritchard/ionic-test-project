# Ionic Test Project
Allows you to ensure that your environment is at least minimally set up.

## Prerequisites
You'll need XCode for IOS development and Android tools for Android development. IOS can only be developed on Mac.

## Build
1. You'll need cordova and ionic: `npm install -g cordova ionic`
2. If you want to develop for IOS, you'll also need to `npm install -g ios-deploy ios-sim`
3. Add desired platform, can install both on Mac: `ionic platform add [ ios | android ]`
4. Build platform: `ionic build [ ios [ --device ] | android ]`

## Run
#### Web App
`ionic serve`

#### Android
* Emulate: `ionic emulate android`, note that you really need hardware support.
* Run on device: `ionic run android`

#### IOS
* Emulate: `ionic emulate ios`
* Run on device: `ionic run ios --device`
