# 🔒 Privacy Policy — Είσαι Νηφάλιος; (Sober Check · 18+)

**Last updated:** November 28, 2026  
**Developer:** Giannis Oikonomakis ([jemangr.app](https://jemangr.app/el/))

## 1. 100% On-Device Sensor & Audio Processing

**Είσαι Νηφάλιος; (Sober Check)** (`app.jemangr.eisainifalios`) executes all gameplay locally inside your device:
- **Motion / Orientation (`DeviceOrientationEvent`):** Used strictly in real time during Stage 1 to move the spirit-level bubble on screen. Zero motion logs leave your device.
- **Microphone Audio (Stage 3, Optional):** When microphone permission is granted, live audio amplitude energy (RMS) is analyzed transiently in memory solely to animate the local waveform and compute speech clarity energy. **Audio is never recorded, stored, uploaded, or transmitted.** If you deny microphone access, you can complete Stage 3 seamlessly using the 4-word touch-order fallback.
- **Generated 9:16 Result Cards:** Rendered strictly in-memory on an HTML5 `<canvas>` locally and saved or shared only when you explicitly tap Save or Share.
- **Version Update Check:** Performs a lightweight read-only fetch to GitHub Releases `version.json` solely to inform you if a newer APK build exists.

## 2. Advertising, Consent & In-App Unlock (Android)

The Android app integrates optional rewarded videos and post-result frequency-capped interstitials via Google AdMob (`@capacitor-community/admob`, configured with mature `MA` content rating) alongside Google UMP GDPR consent dialogs where applicable, plus an optional **Party Pass Pro** one-time unlock via Google Play Billing. No user accounts or personal cloud databases are maintained.

## 3. Entertainment-Only Disclaimer (18+)

⚠️ **18+ Είσαι Νηφάλιος;** is strictly an adult party entertainment game and **NOT** a medical, forensic, or breathalyzer device. Do **NEVER** drive after consuming alcohol regardless of any game score.

Copyright © 2026 Giannis Oikonomakis (jemangr.app). All Rights Reserved.
