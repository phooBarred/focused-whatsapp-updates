# Focused WhatsApp downloads

[Download version 0.7.5](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.7.5/focused-whatsapp-0.7.5.apk) · [Release details](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.7.5)

Focused WhatsApp is an experimental Android 12+ app for limiting WhatsApp Status and Channels. Chats and calls remain available. This repository contains public APK downloads; it is not the source repository.

Install the APK over the existing app; do not uninstall first. Android asks you to approve installation. Updates preserve settings and waits. Open the app afterward and check the phone setup checklist and Accessibility service.

For future updates, use **Settings → About → Check for updates → Download and install**. Installation is available while protection is locked. Android may ask you to allow installations from Focused WhatsApp once. New installations start with protection off, no password, and a one-minute delay; existing settings are preserved when updating.

## This release

Focused WhatsApp 0.7.5

- Google backup now uses Google Drive's hidden app storage, with account selection, Back up now, Restore backup and scheduled backups. No folder picker.
- After updating, open Settings → Google backup, sign in, grant hidden app storage access, then choose Back up now to save this phone's settings. Connecting alone does not upload or overwrite anything.
- Keeps protection, waits, schedules, allowances and passwords on the phone unchanged. Restore still requires protection off or unlocked. Existing Firebase backups are left untouched and are not imported automatically.
- Protects conflicting copies and retries interrupted uploads without creating another file. Permission, full-storage and connection errors have different recovery messages.

Validation: local JVM tests, debug/release lint and builds, and three Android 12 backup/UI regression cases passed. The release also requires the complete Android CI suite, including installer tests. Real Google account consent, Drive writes/restores and Samsung background scheduling still need phone confirmation; emulator and synthetic HTTP tests do not establish those outcomes.

Install this update over the existing app. Do not uninstall first.

## History and limitations

Earlier downloads and their notes remain in [Releases](https://github.com/phooBarred/focused-whatsapp-updates/releases). Screen recognition depends on the WhatsApp interface. Synthetic emulator tests do not establish real WhatsApp, Samsung, or Andoff compatibility. This is not a tamper-proof blocker.

The previously reported Google Play Protect harmful-app warning has not been resolved or proven fixed by this release. Blocking may briefly pause during installation; reopen the app afterward to check protection. Google sign-in, scheduled backups, and cross-install restore still require physical-device validation.

Screen content stays on the phone. Optional Google backup saves configuration only; it does not back up protection activation, waits, access sessions, today's usage, or phone permissions.

Account backups include a salted password verifier, never the plaintext password, messages, or screen content. New backups use Google Drive's hidden app storage with account/app access controls; they are not end-to-end encrypted. Copies made by version 0.7.4 or earlier remain in Firebase under its project administration and are not automatically imported or deleted. Android automatic backup is disabled. Signing out keeps local settings and the saved cloud copy. APKs contain no personal profile, saved password, lock state, or developer backup.
