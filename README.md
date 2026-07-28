# Rai City Run Android APK Project

This is a native Android WebView game project. Netlify or any website hosting is not required.

## Build APK on GitHub (phone-friendly)
1. Create a new GitHub repository.
2. Upload all project files, including the `.github` folder.
3. Open **Actions > Build Android APK > Run workflow**.
4. Download the `Rai-City-Run-APK` artifact and extract `app-debug.apk`.

## Android Studio
Open this folder in Android Studio and select **Build > Build APK(s)**.

## Ads
The project uses Google's official test AdMob IDs. Before publishing, replace:
- App ID in `app/src/main/AndroidManifest.xml`
- Interstitial and Rewarded IDs in `MainActivity.java`

Never publish with test IDs as your final monetization setup.
