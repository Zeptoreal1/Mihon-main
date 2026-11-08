# Mihon: deliberately cursed UI edition

This source-only fork takes Mihon and intentionally makes the UI chaotic and ugly, as requested.

## What was changed

- The **Default** light and dark palettes have clashing lime, magenta, cyan, orange, purple and yellow.
- The app defaults to the Default (cursed) theme for **new** installations rather than dynamic Monet colours.
- A permanent obnoxious banner sits above the home tabs. Tabs are loudly relabelled, but still navigate normally.
- Thin multicolour strips decorate screens using the shared Scaffold.
- Shared card corners, borders, and section headings are intentionally mismatched.
- Shared button corners use irregular shapes.
- Settings rows alternate between loud contrasting surface colours and their headings have warning borders.
- The More page features an unmissable UI disaster warning.

## Keeping it usable

Manga library storage, tracking, reading engines, network calls, and download logic were not changed. This is **not** a release APK; it is Android/Kotlin source. Existing installations that have saved a different theme may need to select **Default** under Appearance to see the neon colour theme. Other themes were preserved.

This is an unofficial modification of upstream Mihon; retain the existing LICENSE, credit, and upstream notices.

## Build

Open the project in Android Studio or use the included Gradle wrapper with the proper JDK, Android SDK and Gradle dependencies installed. The ZIP was validated structurally but not compiled as an Android APK in this environment.
