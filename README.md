# Paddhu Pusthakam

Personal build of [Cashew](https://github.com/jameskokoska/Cashew), a Flutter budgeting app. Not distributed.

## Changes from upstream
- App renamed to Paddhu Pusthakam
- Own Firebase project for Google sign-in
- Unused platform folders and promotional files removed
- GitHub Actions workflow that builds a signed release APK

## Build
Run the "Build Android APK" workflow in the Actions tab. It needs the repository secrets KEYSTORE_BASE64, KEYSTORE_PASSWORD, KEY_PASSWORD and KEY_ALIAS.

Raise the build number in `budget/pubspec.yaml` (the number after `+`) before each update.

## License
GPL-3.0, inherited from upstream. See `LICENSE`.
