# I.E.C Sakyong Nepali Christian Bhajan Lyrics & Chords — APK build project

This project packages the website into a basic Android WebView app. It is not itself an APK; GitHub Actions compiles the APK in the cloud.

## Build using a phone
1. Create a GitHub repository and upload **all files and folders** from this project. Ensure the hidden `.github/workflows/build-apk.yml` is included.
2. Open the repository's **Actions** tab and enable workflows if asked.
3. Choose **Build I.E.C Sakyong APK** → **Run workflow** (or wait for the push-triggered run).
4. When the run succeeds, open it and download the `IEC-Sakyong-Bhajan-APK` artifact. Extract the downloaded ZIP to get `app-debug.apk`.
5. On Android, tap the APK to install; allow installation from that source if Android asks.

This is a debug APK for testing, not a Google Play release. The app currently uses sample/demo lyrics; replace them with lyrics you have permission to publish.
