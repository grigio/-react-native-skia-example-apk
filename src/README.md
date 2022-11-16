# React Native Skia Example apk

The official example app has [some issues](https://github.com/Shopify/react-native-skia/issues/1098) to produce a valid Android apk so I imported the official one in a new React Native project to test the apk on a real Android device.

### Dependencies check

- Gradle / Java compatibility table https://docs.gradle.org/current/userguide/compatibility.html
- Check to have a valid `$ANDROID_HOME` env variable

```
ls $ANDROID_HOME
build-tools  emulator  ndk      platforms       skins    system-images
cmake        licenses  patcher  platform-tools  sources  tools

java -version 
openjdk version "17.0.5" 2022-10-18
OpenJDK Runtime Environment (build 17.0.5+1)
OpenJDK 64-Bit Server VM (build 17.0.5+1, mixed mode)

npx react-native -version 
9.2.1
```


### Usage

```
yarn

yarn android-build-apk

yarn android-install-apk
```