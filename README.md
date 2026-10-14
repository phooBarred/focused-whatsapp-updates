# Focused WhatsApp

## [Download the Android APK](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.3.2/focused-whatsapp-0.3.2.apk)

**Version 0.3.2 preview · Android 12 or later**

[Release notes and checksum](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.3.2)

Focused WhatsApp blocks recognized Status, Channels, and Updates screens in WhatsApp and WhatsApp Business while keeping chats and calls available.

### Install or update

1. Open the APK download link on your Android phone.
2. Allow your browser to install apps if Android asks, then confirm installation.
3. If you already have Quiet Updates or Focused WhatsApp, install over it. **Do not uninstall first.** The app ID and signing certificate are unchanged, so your protection settings are preserved.
4. Open Focused WhatsApp and check the phone setup checklist and protection status. Fresh installations start with protection off, no password, and a one-minute delay in delay-only mode. Android may restore the installing user's own settings backup.

Starting with 0.3.0, use **About → Check for updates** for future updates. Downloading and installing an update does not require unlocking protection or waiting out a timer. Android may require a one-time permission to install updates from Focused WhatsApp.

### New in 0.3.2

- **Download and install** opens Android’s installation prompt automatically once the APK is verified.
- If install-source permission is needed, granting it and returning continues automatically.
- Declining permission or canceling installation waits for an explicit retry; retries keep the downloaded APK.
- Protection settings and running waits are preserved.

Older versions still show their separate Download and Install update buttons when installing this release. The new combined button is available after installing 0.3.2.

### Preview limitations

The app uses Android accessibility services. Recognition depends on WhatsApp's current interface and is experimental. Samsung-specific behavior, device-owner restrictions, and Google backup transport require device testing. Blocking may briefly pause while Android installs an update; reopen the app afterward to check protection. Rebooting restarts a pending unlock wait in full.

### Privacy and distribution

This repository contains public APK downloads and release information only. Source code is maintained separately. No personal profile, saved password, lock state, or developer backup is bundled in the APK. Screen content stays on the phone; manual update checks and downloads connect to GitHub.

App ID: `app.quietupdates`  
Release certificate SHA-256: `b2bca291efb07b852b83d766a7ae5fb8ecd800b515b07de643d43c6fa31aeb83`
