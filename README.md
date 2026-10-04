# CamMatch – APK Project

## Paagi 1: GitHub (pinakasayon, walay install)
1. Himo og bag-ong repo sa github.com (branch: main), i-upload ang tanang sulod niini nga folder, apil ang `.github`.
2. Adto sa **Actions -> Build APK -> Run workflow** (o mo-auto run pag-push).
3. Pagkahuman (~5 min), i-download ang **CamMatch-APK** sa Artifacts. Naa'y `app-debug.apk`.
4. Ipasa sa phone ug i-install (i-allow ang "Install unknown apps").

## Paagi 2: PWABuilder
I-host ang `www/` (Netlify / GitHub Pages), dayon i-paste ang link sa pwabuilder.com -> Package for Android.

## Paagi 3: Android Studio (local)
Kinahanglan: Node 18+, Android Studio, JDK 17.
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android      (Build > Build APK)

## Real photos
Ibutang sa `www/photos/` ang mga file nga nakalista sa `PHOTOS.txt`, dayon i-build pag-usab.
Gamita ang imong kaugalingong litrato o licensed/press images sa brand.
