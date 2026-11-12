---
layout: default
title: Brkt Privacy Policy
permalink: /brkt/privacy/
---

# Privacy Policy for Brkt


**Last updated:** 12 November 2026

This Privacy Policy describes how **unusedmethod** ("we", "us", or "our") handles information in connection with the **Brkt** game (the "App"). By installing and using the App, you agree to the practices described in this policy.

## 1. Overview

Brkt is a Breakout-style arcade game. We are committed to your privacy. **The App does not collect, transmit, share, or sell any personal or personally identifiable information.**

## 2. Data We Do Not Collect

The App does **not** collect or transmit:

- Personal information (name, email, phone number, address)
- Device identifiers (advertising ID, Android ID, IMEI)
- Geolocation data
- Usage or analytics data
- Crash logs or diagnostic data to remote servers
- Photos, contacts, messages, or media files
- Account credentials (the App has no login or account system)

The App has **no internet access** and does not communicate with any external server. When played in a web browser, the App's files are downloaded from the site that hosts them; once loaded, the App sends nothing back.

## 3. Data Stored Locally on Your Device

The App stores the following information **on your device only** using Godot's `user://` storage. This data never leaves your device.

| File | Purpose | Contents |
|---|---|---|
| `user://progress.cfg` | Remembers your unlocked levels and best score in each play mode | Three integers: `unlocked_level`, `high_score` (Classic), `high_score_shield` (Shield) |
| `user://saves/<id>.cfg` (one per saved run) | Level-start checkpoints you can resume | The run name you type (free text, up to 80 characters), play mode (Classic or Shield), level, score, difficulty, level seed, level generator version, a SHA-1 fingerprint of the level layout, and the last-saved time. The file name `<id>` is the time the run was created. |
| `user://settings.cfg` | Remembers your preferences | Display (CRT effect and its parameters, fullscreen, V-Sync), accent colour, access options (text size, paddle sensitivity, reduced effects, ball tail, launch setup mode, whether setup hints have been shown), sound volumes and input bindings |
| `user://logs/` (Windows and Linux only) | The Godot engine's technical logs of the last few sessions | Engine messages (such as the graphics device in use) and error messages |

Run names are free text and stay on your device. Please do not type personal details, such as a real name.

Where it is kept and how to remove it:

- **Android:** the App's private storage, excluded from Android backup. Clear the App's storage in Android Settings or uninstall the App.
- **Web:** the browser's storage for the site that hosts the App. Clear that site's data in your browser.
- **Windows and Linux:** the App's user data folder. Delete that folder.
- Saved runs can be deleted at any time from **Resume Run** in the App.

This data is:

- Not personal or identifying (unless you type such details into a run name)
- Not transmitted anywhere
- Not shared with third parties

## 4. Permissions

The App requests one Android permission, **Vibrate**, used only for short haptic feedback during play. It can be turned off in Settings → Controls & Access → Haptics, and it gives the App no access to any data. The App does not request:

- Internet access
- Location
- Camera or microphone
- Contacts
- Storage (beyond the App's own private storage, which requires no permission)
- Notifications
- Phone state

## 5. Children's Privacy

The App is suitable for all ages and does not knowingly collect any information from anyone, including children under 13. Because the App collects no data at all, it is compliant with the Children's Online Privacy Protection Act (COPPA) and the Google Play Families Policy by default. There is no age gate, account creation, or social feature.

## 6. Third-Party Services

The App does **not** use any third-party services, SDKs, or libraries that collect data. Specifically, the App does **not** include:

- Advertising SDKs (e.g., AdMob)
- Analytics SDKs (e.g., Firebase, Google Analytics)
- Crash reporting SDKs (e.g., Crashlytics)
- Social or login SDKs
- In-app purchase frameworks that transmit personal data

## 7. Data Security

Because the App does not collect or transmit any data, there is no risk of personal data exposure through the App. Locally stored progress, saved runs and settings are kept in the App's own storage area; on Android, the system isolates it from other Apps.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be posted within the App's distribution listing and in the App (About, Privacy Policy), and reflected by the "Last updated" date above. Continued use of the App after a change constitutes acceptance of the updated policy.

## 9. Contact Us

If you have any questions about this Privacy Policy or the App's data practices, please contact us:

- **Email:** [unusedmethod@gmail.com](mailto:unusedmethod@gmail.com)
- **Developer:** unusedmethod

## 10. Summary

In short: **Brkt collects no data. Nothing leaves your device. The only permission is Vibrate, for haptic feedback. No third-party SDKs are used.**