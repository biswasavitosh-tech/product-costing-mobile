# Product Costing Mobile APK project

This is an Android WebView wrapper for the offline Product Costing Calculator.

## Build APK using GitHub (phone-friendly)
1. Upload the contents of this folder into the root of your GitHub repository (not the ZIP file itself).
2. Ensure `.github/workflows/build-apk.yml` is present.
3. Open the repository's **Actions** tab.
4. Select **Build Product Costing APK**.
5. Tap **Run workflow** and confirm.
6. Open the latest successful run.
7. At the bottom, under **Artifacts**, download `product-costing-apk`.
8. Extract the downloaded artifact ZIP and install `app-debug.apk` on your Android phone.
   Android may ask you to allow installation from that browser/file manager.

## Important
- This workflow builds the APK from the Android project in this repository.
- Do not upload only the HTML file or the project ZIP; the workflow expects the project files at the repository root.
- The APK is a debug build. Android may show a warning when installing an APK downloaded outside the Play Store.
