# TerraShield Android App

This project wraps the uploaded TerraShield website in a native Android WebView so it can be opened and built as an Android application.

## Open
1. Install Android Studio.
2. Open this `TerraShieldAndroid` folder.
3. Let Gradle sync.
4. Connect an Android phone with USB debugging enabled, or create an emulator.
5. Click **Run**.

## Build APK
In Android Studio:
**Build → Build App Bundle(s) / APK(s) → Build APK(s)**

The debug APK will normally be under:
`app/build/outputs/apk/debug/app-debug.apk`

## Included
- The uploaded TerraShield UI and JavaScript.
- Portrait Android app shell.
- Internet permission for the Google Fonts used by the website.
- Location permissions prepared for future GPS integration.
- WebView file chooser support.
- App label: TerraShield.
- Package: `com.terrashield.app`

Note: the current website itself uses demo risk data and its report photo control is a UI toggle rather than a real upload field. This conversion preserves that behavior rather than inventing backend functionality.
