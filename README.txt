INFINITY RAGDOLL - ANDROID PROJECT
=================================

This is an Android Studio project that packages the existing HTML/Three.js game
inside a fullscreen landscape Android WebView.

BUILD AN APK
1. Install Android Studio (current stable) on a computer.
2. Open this folder in Android Studio.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK is normally created at:
   app/build/outputs/apk/debug/app-debug.apk

NOTES
- This ZIP is the Android source project, NOT a precompiled APK.
- The game loads Three.js and cannon-es from jsDelivr, so internet is required
  when launching the game.
- minSdk 26 means Android 8.0 or newer.
- Landscape fullscreen is enabled.
- A computer with Android Studio is required to compile this project.
