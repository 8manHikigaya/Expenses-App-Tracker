# Pocket Ledger

Minimal offline expense tracker. All data stays on your phone.

## Get the APK (no Android Studio needed)
1. Create a new GitHub repository and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab. The "Build APK" workflow runs automatically (about 5 minutes).
3. Open the finished run and download **pocket-ledger-apk** under Artifacts. Unzip it to get `app-debug.apk`.
4. Copy it to your phone, open it, and allow "Install unknown apps" when Android asks.

## Editing the app
Everything lives in `www/index.html`. Change it, push, and a new APK is built.

## Notes
- Data is stored inside the app. Uninstalling or clearing app data erases it, so use **Export CSV** in settings now and then.
- This is a debug build (unsigned for Play Store). Fine for personal use.
