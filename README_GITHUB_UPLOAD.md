# STAR COMMUNICATION — GitHub APK Build

## Upload to a NEW GitHub repository
Upload the **contents of this folder** to the ROOT of the repository.
Do NOT upload this folder itself as a single nested folder, and do NOT upload the ZIP file itself.

The root must look like this:

- `settings.gradle`
- `build.gradle`
- `gradle.properties`
- `app/build.gradle`
- `app/src/main/AndroidManifest.xml`
- `app/src/main/assets/index.html`
- `app/src/main/java/com/starcommunication/isp/MainActivity.java`
- `.github/workflows/build-apk.yml`

## Build
After committing the files:
1. Open **Actions**.
2. Select **Build STAR COMMUNICATION APK**.
3. Choose **Run workflow** and run it on `main`.
4. When successful, open the run and download artifact **STAR-COMMUNICATION-debug-apk**.
5. Extract the artifact ZIP and install the APK on Android.
