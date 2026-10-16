# Focused WhatsApp

## [Download the Android APK](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.5.0/focused-whatsapp-0.5.0.apk)

**Version 0.5.0 · Android 12 or later**

[Release notes and checksum](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.5.0)

Focused WhatsApp blocks recognized Status, Channels, and Updates screens in WhatsApp and WhatsApp Business while keeping chats and calls available.

### Install or update

1. Open the APK download link on your Android phone.
2. Allow your browser to install apps if Android asks, then confirm installation.
3. If you already have Quiet Updates or Focused WhatsApp, install over it. **Do not uninstall first.** The app ID and signing certificate are unchanged, so your protection settings are preserved.
4. Open Focused WhatsApp and check the phone setup checklist and protection status. Fresh installations start with protection off, no password, and a one-minute delay in delay-only mode. Restoring saved settings requires selecting your Google account and explicitly confirming restore inside the app.

Use **About → Check for updates** for future updates. About is under Settings. Downloading and installing an update does not require unlocking protection or waiting out a timer. Android may require a one-time permission to install updates from Focused WhatsApp.

### New in 0.5.0

- Choose an access window from 1 minute to 3 days, or Permanent.
- Change that preference while locked without a delay or password; it applies to the next window only.
- Permanent access survives a phone restart until you tap End access window now. WhatsApp blocking stays on.
- Google backup includes the chosen length, never an open access session. Existing installations keep five minutes.

### New in 0.4.2

- Save controls appear only after editing; unchanged forms have one top-right X.
- Clear discard questions: red X keeps editing; green check discards.
- Explicit Save for appearance and backup schedules; failed saves preserve your draft.
- Protection rules, checklist ticks, and update/install access stay the same.

### New in 0.4.1

- Updated unlocking help for the selected method, stronger settings, and automatic delay reductions.
- Green confirmation checks and red cancel/close icons. A single X appears at the top right.
- Consistent Focus card spacing and matching top/bottom dialog margins.
- Green pass, yellow unknown, and red fail statuses on the phone setup checklist.
- Google backup stays under Settings; the extra About button has been removed.

### New in 0.4.0

- Separate Focus and Settings pages, with clearer buttons, icons, and consistent dialogs in light and dark mode.
- Google account backup inside the app: select an account, back up now, set a schedule, or restore. No folder picker is needed.
- Daily backup is the default after connecting an account. Manual only, every 15 minutes, hourly, and every 6 hours are also available; Android can defer background work.
- Backups include the waiting period, unlock method, password verifier, appearance, and backup schedule. Protection on/off, running waits, temporary access, pending changes, and phone permissions stay local.
- Restore is available only with protection off or settings unlocked. It preserves existing protection state and cannot replace a different existing password.
- The Settings footer and About display Version followed by the installed version.

### Current limitations

This is an experimental release below 1.0. The app uses Android accessibility services; recognition depends on WhatsApp's current interface. Real WhatsApp/WhatsApp Business behavior, Samsung-specific behavior, device-owner restrictions, Google account sign-in, scheduled backups, and cross-install restore still require phone testing. Blocking may briefly pause while Android installs an update; reopen the app afterward to check protection. Rebooting restarts a pending unlock wait in full.

The previously reported Google Play Protect harmful-app warning has not been resolved or proven to be fixed by this release.

### Privacy and distribution

This repository contains public APK downloads and release information only. Source code is maintained separately. No personal profile, saved password, lock state, or developer backup is bundled in the APK. Screen content stays on the phone. Manual update checks and downloads connect to GitHub.

Optional Google account backup uses Firebase with access restricted to the signed-in account. It contains saved preferences and a salted password verifier, never the plaintext password, messages, screen content, or active protection state. Cloud backup is not end-to-end encrypted; project administrators can administer the database. Android automatic backup is disabled. Signing out keeps your local settings and the saved cloud copy.

App ID: `app.quietupdates`  
Release certificate SHA-256: `b2bca291efb07b852b83d766a7ae5fb8ecd800b515b07de643d43c6fa31aeb83`
