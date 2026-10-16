UET Card Verifier - Android APK (QR scan with the phone camera)
================================================================

FASTEST WAY TO GET THE APK (about 5-10 minutes, no coding)
1. Make a free account at github.com and click New repository (any name, Private is fine).
2. Click "uploading an existing file" and drag in EVERYTHING from this folder
   (app, build.gradle, settings.gradle, gradle.properties, and the hidden folder .github).
   If you cannot see .github, unzip first, then drag the whole folder content.
   Press Commit changes.
3. Open the Actions tab -> "Build APK" -> it starts by itself (or press Run workflow).
4. When it shows a green tick (about 3-5 minutes), open the run and download the file
   "UET-Card-Verifier-apk" under Artifacts. Unzip it: app-debug.apk is inside.
5. Copy app-debug.apk to the phone, tap it and allow "Install unknown apps".

ANDROID STUDIO WAY
Open this folder in Android Studio -> wait for Gradle sync -> Build > Build APK(s).
The file is app/build/outputs/apk/debug/app-debug.apk

USING THE APP
1. Open "UET Card Verifier", type the Security key (copy it from the card program,
   section 03b) and tap Save key. This is needed once.
2. Tap Live camera scan (or Take a photo of the QR code) and point at the card.
3. Optional: load UET_Verifier_Data.json (made by the card program) to see photos
   and to block cancelled / replaced cards.

The app needs no internet. Camera permission is asked on first use.
