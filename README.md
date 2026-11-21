# LedgerFlow Android wrapper

This project packages the existing LedgerFlow Business Manager website in a simple Android WebView app.

## What it does
- Installs as an Android app named **LedgerFlow**.
- Opens the existing hosted business manager.
- Uses the same online database as the website, so records remain available across devices.
- Requires an internet connection.

## Build the APK with minimal computer work

1. Sign in to GitHub and create a **new private repository** named `ledgerflow-android`.
2. Upload the contents of this ZIP to the repository (not the ZIP file itself), keeping the folder structure.
3. Open the repository's **Actions** tab.
4. Select **Build LedgerFlow APK** and press **Run workflow**. (A push to `main` also starts a build.)
5. When the workflow finishes, open its run and download the **LedgerFlow-Android-APK** artifact.
6. Extract the downloaded artifact ZIP on your Android phone and install `app-debug.apk`. If Android asks, allow installation from that source.

## Important
- This is a lightweight online wrapper, not an offline copy of the web application.
- Business records remain on the existing AppDeploy backend.
- The APK is a debug-signed test build. A Play Store release or broadly distributed production APK should be signed with a private release key.
- The APK has not been compiled yet; GitHub Actions performs that build.
