# Android Jitsi Meet to grommunio-meet transformation

## Installation

- `npm install`

## Run the app

- run normally via Android Studio

## Build the app

- get the keystore -> current keystore in `/Users/jensherman/Desktop/grommunio-chat/Android/config-files/grommunio-keystore.keystore`
- get the keystore pwd & alias -> see `/Users/jensherman/Desktop/grommunio-chat/Android/config-files/gradle.properties`

### Build debug .apk
via Android Studio

- Build > Build Bundle(s) / APK(s) > Build APK(s)

-> `./android/app/build/outputs/apk/debug/app-debug.apk`

### Build release
via Android Studio

- Build > Generate Signed Bundle / APK...
- use "Key store password" as "Key password"

 -> `./android/app/release/app-release.apk` / `./android/app/release/app-release.aab`


## Debugging

### Reinstall node modules

`rm -rf node_modules/` \
`npm run clean` \
`npm install`
