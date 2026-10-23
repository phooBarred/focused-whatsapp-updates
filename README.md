# Focused WhatsApp

## [Download the Android APK](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.7.1/focused-whatsapp-0.7.1.apk)

**Version 0.7.1 · Android 12 or later**

[Release notes and checksum](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.7.1)

Focused WhatsApp blocks recognized Status, Channels, and Updates screens in WhatsApp and WhatsApp Business while keeping chats and calls available.

### Install or update

1. Open the APK download link on your Android phone.
2. Allow your browser to install apps if Android asks, then confirm installation.
3. If you already have Quiet Updates or Focused WhatsApp, install over it. **Do not uninstall first.** The app ID and signing certificate are unchanged, so your protection settings are preserved.
4. Open Focused WhatsApp and check the phone setup checklist and protection status. Fresh installations start with protection off, no password, and a one-minute delay in delay-only mode. Restoring saved settings requires selecting your Google account and explicitly confirming restore inside the app.

Use **About → Check for updates** for future updates. About is under Settings. Downloading and installing an update does not require unlocking protection or waiting out a timer. Android may require a one-time permission to install updates from Focused WhatsApp.

### New in 0.7.1

- A compact Focus screen with less explanatory text and consistent spacing.
- Phone setup is available from the top-right checklist icon and from Settings. Unlock help is beside the access-card title.
- Full-size touch targets and scrolling when enlarged text or a smaller screen needs it. Existing protection settings and waits are preserved.

### New in 0.7.0

- Give WhatsApp and WhatsApp Business independent protection modes, weekly schedules, and daily viewing allowances, or share an allowance across both apps.
- Set different limits by weekday, using Minutes or Hours with decimal input and readable durations.
- Only recognized Status, Channels, and Updates viewing consumes the allowance; chats and calls stay available. Usage stays on the phone and does not reset when you edit or restore settings.
- Rounded, borderless buttons and selections, one row of weekdays with only selected days highlighted, compact time fields, and help beside individual settings.
- Settings access still uses your existing delay/password rules. Increasing allowed access requires unlocking; stronger protection can be saved while locked.

### New in 0.6.0

- Set weekly blocking periods by day, with multiple periods per day and overnight support.
- View a clear daily ON/OFF timeline and the next scheduled switch.
- Overlapping periods are rejected, including overnight conflicts.
- Scheduled breaks keep settings locked. Adding blocked time is allowed while locked; reducing it requires your existing unlock method.
- Existing installations keep Always on until you save a schedule. Account backups include the weekly plan, never protection activation or live access sessions.

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
