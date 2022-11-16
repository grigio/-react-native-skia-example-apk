## React Native Skia Example Android app

The official app do not work out of the box so I created one from scratch to produce a valid apk.

### Check dependencies for Gradle and environment

```
java -version
openjdk version "17.0.5" 2022-10-18
OpenJDK Runtime Environment (build 17.0.5+1)
OpenJDK 64-Bit Server VM (build 17.0.5+1, mixed mode)
```

### You also need a valid $ANDROID_HOME

```
ls $ANDROID_HOME
build-tools  emulator  ndk      platforms       skins    system-images
cmake        licenses  patcher  platform-tools  sources  tools
```

### Compile and install the production APK on the Android device

```
yarn

yarn android-build-apk

yarn android-install-apk
```