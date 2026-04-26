---
layout: default
title: Privacy Policy — Amakni
---

# Privacy Policy — Amakni (أماكني)

**Last updated:** April 26, 2026
**App:** Amakni — Location Saver
**Developer:** Mahmoud Ashraf
**Contact:** mahmoud55551017@gmail.com

Amakni is a privacy-first, offline-first location saver. We designed it so your data stays on your device. This policy explains what the app accesses, why, and what we do (and do not) collect.

---

## 1. Data we do NOT collect

We do not collect, transmit, sell, or share any of the following:

- Your saved places (names, notes, addresses, coordinates).
- Your photos.
- Your voice recordings or transcripts.
- Your contacts.
- Your browsing or usage analytics.
- Any personal identifiers tied to you (name, email, phone).

All saved places are stored **locally on your device** in a SQLite database.

---

## 2. Permissions we request and why

### Location (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`)
Used **only** when you tap "Use Current Location" while adding a place. The coordinates are saved into your local database. They are never sent to any server.

### Microphone (`RECORD_AUDIO`)
Used **only** when you tap the microphone icon to dictate a place name, note, or human-readable directions. Audio is processed by your device's built-in speech-to-text engine (Google on Android, Apple on iOS) and converted into text locally. Amakni does not record, store, or transmit any audio. The resulting text is saved into your local database only.

### Foreground Service / Foreground Service Location (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_LOCATION`)
Required by the Android system whenever the app reads location while in the foreground. No background tracking is performed.

### Photos / Gallery (via image picker)
Used **only** when you choose to attach a photo to a place. Photos are stored locally inside the app's sandbox. They are not uploaded.

### Internet
Used to:
- Resolve coordinates to a human-readable address via the platform's built-in geocoder.
- Open external map applications (Google Maps, Apple Maps, Waze, Uber).
- Check for app configuration updates (see "Subscription & device identifier" below).

No place data is sent over the network.

---

## 3. Subscription & device identifier

If you choose to upgrade to Amakni Premium, the app generates a random per-device identifier and stores it in your device's secure storage (Keychain on iOS, Keystore on Android). You may be asked to share this identifier when contacting support to activate your account.

We use **Google Cloud Firestore** to store:
- Your random device identifier (no name, email, or phone is collected).
- Whether your device is marked as Premium.

Free users do not have any record on our servers. The device identifier is only created and uploaded after you initiate a purchase request.

---

## 4. Third-party services

- **Google Cloud Firestore** — used to store premium activation status keyed by the random device identifier described above. See Google's privacy policy: https://policies.google.com/privacy
- **Apple Speech / Google Speech-to-Text** — your device's built-in dictation engine. Audio is processed by the operating system; Amakni never sees raw audio. See Apple's and Google's respective privacy policies.
- **Google Maps / Apple Maps / Waze / Uber** — opened externally if you tap one of the navigation buttons. Once opened, those apps are governed by their own privacy policies.

We do not use Firebase Analytics, Crashlytics, AdMob, or any advertising or tracking SDK.

---

## 5. Children's privacy

Amakni is not directed at children under 13. We do not knowingly collect data from children.

---

## 6. Data retention and deletion

All place data is stored locally. Uninstalling the app removes all locally stored data (places, photos, secure storage). To reset premium status or delete your random device identifier from our Firestore database, email **mahmoud55551017@gmail.com** with your device identifier (visible in the in-app paywall sheet) and we will remove the record within 30 days.

---

## 7. Security

- Local database files are stored in the app's private sandbox.
- The device identifier is stored in iOS Keychain / Android Keystore.
- All network traffic uses HTTPS.

---

## 8. Changes

If this policy changes, we will update the "Last updated" date and post the new version at the same URL.

---

## 9. Contact

Questions or requests:
**Mahmoud Ashraf — mahmoud55551017@gmail.com**
