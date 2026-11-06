# მითიური ლეგენდები — Android

Idle RPG თამაში Android-ისთვის. თამაში თავად არის `app/src/main/assets/index.html`, ხოლო `MainActivity.java` მას WebView-ში აჩვენებს (ინტერნეტის გარეშე).

- **აწყობა:** GitHub → Actions → „Build Android app“ → Run workflow. მზა `.aab` და `.apk` ჩანს Artifacts-ში.
- **ხელმოწერა:** საჭიროა 4 GitHub Secret: `KEYSTORE_BASE64`, `KEYSTORE_PASSWORD`, `KEY_ALIAS`, `KEY_PASSWORD`.
- **ვერსია:** versionCode = Actions-ის build-ის ნომერი, ავტომატურად იზრდება.
- **კონფიდენციალურობის პოლიტიკა:** `docs/privacy-policy.html` (GitHub Pages).

Package: `ge.mythiclegends.idlerpg` · minSdk 24 · targetSdk 36
