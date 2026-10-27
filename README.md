# GENZ PRO — Android Photo Pose App

A native Android starter project using Kotlin and Jetpack Compose, with a cloud build workflow so you can build the APK from an Android phone.

## Features
- Gen-Z dark UI with neon-purple accents
- 24 pose ideas for boys, girls, friends, and couples
- Search and category filters
- Favorite poses saved on the device
- Pose detail cards with posing tips
- Built-in pose list works offline

## Current limitations
- Pose artwork is emoji-style placeholders, not real reference photos yet.
- Camera capture, accounts, and online pose downloads are not implemented.
- This project has not been compiled or device-tested here.
- The generated debug APK is for testing/personal installation, not a Play Store release.

## Build the APK using only an Android phone
You need a GitHub account. In your phone browser, you can use GitHub's website; use **Desktop site** if the mobile layout hides options.

1. Download this ZIP and extract it if your phone's file manager supports extraction.
2. Create a GitHub repository named `genz-android`.
3. Upload the *contents* of this folder to the repository, preserving all folder paths. Do not upload only the ZIP file.
4. Open the repository's **Actions** tab and select **Build GENZ APK**.
5. Tap **Run workflow**. Uploading files to the `main` branch also triggers the build.
6. When the workflow finishes successfully, open the run and download the `GENZ-debug-apk` artifact.
7. Extract the downloaded artifact ZIP and tap `app-debug.apk` to install. If prompted, allow your browser or file manager to install unknown apps.

## Package
- App ID: `com.genz.posevibe`
- Minimum Android: Android 7.0 (API 24)
