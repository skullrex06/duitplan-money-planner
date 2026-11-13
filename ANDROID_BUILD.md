# DuitPlan Android APK

DuitPlan is packaged as an Android app with Capacitor. The app remains offline-first:
- The web interface is bundled inside the APK.
- Financial records remain on the device.
- No login, cloud database, or bank connection is configured.
- Export your JSON backup regularly; uninstalling the app or clearing its storage can remove local records.

## Build APK
1. Open the repository's **Actions** tab.
2. Select **Build DuitPlan Android APK**.
3. Tap **Run workflow** and confirm.
4. When the run completes, open its summary and download the **DuitPlan-Android-debug** artifact.
5. Extract the ZIP and install `app-debug.apk` on your Android phone. Allow installation from that source if Android asks.

The workflow also runs automatically when the app's web files or Android build configuration change on `main`.

This is a debug APK for testing, not a signed Play Store release.
