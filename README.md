# buildIPA

GitHub Actions workflow that downloads a decrypted IPA and user-supplied `.deb` packages (direct URLs or zip archives), keeps **Theos** + **iOS SDK** + **Cyan** cached on the runner, then injects the DEBs with [Cyan](https://github.com/asdfzxcvbn/pyzule-rw) and uploads a draft release.
