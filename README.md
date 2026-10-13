# MusicFlow — Game Booster (Android)

A starter Android project using Java and the Android SDK. Features:
- Dark neon interface
- Gaming session timer
- Battery percentage
- Approximate RAM use by MusicFlow itself
- Launch list of apps visible to Android's launcher query
- Shortcuts to Android display, battery, and app settings

## Build an APK

### Option A: Android Studio (computer)
1. Install Android Studio with Android SDK Platform 35 and a compatible JDK (17 is recommended for Android Gradle Plugin 8.7.x).
2. Open this `MusicFlow` folder as a project.
3. Let Gradle sync and download the Android Gradle Plugin.
4. Select **Build > Build APK(s)**.
5. The debug APK should appear at `app/build/outputs/apk/debug/app-debug.apk`.

### Option B: Android phone
Use a trusted Android IDE that supports Gradle Android projects (for example, AndroidIDE if compatible with your Android version). Extract the ZIP, open the `MusicFlow` folder, sync Gradle, then build a debug APK. The IDE may need to download Gradle and Android SDK components, so Wi-Fi is recommended.

## Notes / limitations
- This app does not root the phone or change protected system performance settings.
- RAM number is the app process's approximate PSS, not all phone RAM usage.
- Battery temperature is not shown in this starter version.
- The launcher list can include ordinary apps, not only games; Android does not provide a universally reliable game classification API for every installed app.
- FPS overlays, forcing 90/120 Hz, killing other apps, and clearing other apps' cache are not available to an ordinary third-party app on all devices.
- If a Gradle sync error occurs, confirm internet access and Android SDK Platform 35 installation.
