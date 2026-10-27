# Chai Tapri Rush — Android APK project

This wraps your supplied HTML game in a simple Android WebView app. It is not the compiled APK yet; use the GitHub Actions workflow to build the APK.

## Build APK from your phone
1. Sign in to GitHub and create a **new public or private repository** named `ChaiTapriRush`.
2. Upload the contents of this ZIP (the files inside the folder, not the ZIP itself) to the repository. Keep the `.github` folder.
3. Open the repository's **Actions** tab and enable Actions if asked.
4. Choose **Build Chai Tapri Rush APK** → **Run workflow**.
5. When it finishes, open the workflow run, scroll to **Artifacts**, and download `Chai-Tapri-Rush-APK`.
6. Extract the downloaded ZIP; install `app-debug.apk` on your Android phone. If Android asks, allow installs from that browser/file manager.

## Notes
- The game uses JavaScript and browser storage, which this wrapper enables.
- Internet is needed for the game's Three.js CDN dependency.
- This is a debug APK for personal testing, not a Play Store release.
