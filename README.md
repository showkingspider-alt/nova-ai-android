# NOVA AI Android App

This is an Android WebView shell for the NOVA AI web app.

## Important
The APK loads the deployed NOVA AI website. Replace `DEFAULT_URL` in:
`app/src/main/java/com/novaai/app/MainActivity.java`
with your real HTTPS NOVA AI URL before building.

Example:
`https://nova-ai-yourname.vercel.app`

## Build
Open this folder in Android Studio, let Gradle sync, then use:
Build > Build APK(s)

The generated debug APK is normally under:
`app/build/outputs/apk/debug/app-debug.apk`

## Current web project
Use the previously generated `nova-ai.zip` as the web application to deploy first. The Android shell does not contain your Anthropic secret; the AI key must stay on the web app's server-side environment.
