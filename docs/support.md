# Installation and troubleshooting

## Download and install

1. Open [The Geek Network Apps releases](https://github.com/bhengubv/thegeeknetworkapps/releases) and select your app.
2. Match the version and architecture to your device. Download the APK attached to that release.
3. Compare the file's SHA-256 hash with the release notes. On Windows, run `Get-FileHash -Algorithm SHA256 .\your-app.apk`.
4. Open the downloaded APK. If Android prompts you, allow installation for the app that opened the file. You can turn that permission off afterward.

## Android says the app was not installed

Confirm the file ends in .apk, is fully downloaded, and matches your Android version and architecture. If updating an existing app, check that the package name and signing certificate match and that the release is at least as new as the installed version. Avoid uninstalling to work around a signature mismatch. Uninstalling can remove app data.

## Download works, but sign-in or an online feature fails

This hub keeps downloads available independently. Sign-in, payments, and other online features still depend on their services. If a feature fails, note the app version, Android version, exact error, and approximate time. Keep account identifiers, verification codes, and payment details out of public reports.
