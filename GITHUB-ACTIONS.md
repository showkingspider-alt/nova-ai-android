# Build NOVA AI APK from your phone

1. Upload the contents of this project to a GitHub repository.
2. Open the repository and tap **Actions**.
3. Select **Build NOVA AI APK**.
4. Tap **Run workflow** if it is not already running.
5. Wait for the green check mark.
6. Open the completed workflow run and scroll to **Artifacts**.
7. Download **NOVA-AI-debug-apk**.
8. Extract the downloaded ZIP and install `app-debug.apk` on Android.

## Important

Before building, open `app/src/main/java/com/novaai/app/MainActivity.java` and replace:

`https://YOUR-NOVA-AI-DOMAIN.vercel.app`

with the real HTTPS URL of your deployed NOVA AI web app.

This workflow builds a debug APK. A release APK with signing is a separate step.
