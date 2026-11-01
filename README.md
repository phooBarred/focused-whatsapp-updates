# Focused WhatsApp downloads

[Download version 0.7.6](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.7.6/focused-whatsapp-0.7.6.apk) · [Release details](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.7.6)

Focused WhatsApp is an experimental Android 12+ app for limiting WhatsApp Status and Channels. Chats and calls remain available. This repository contains public APK downloads; it is not the source repository.

Install the APK over the existing app; do not uninstall first. Android asks you to approve installation. Updates preserve settings and waits. Open the app afterward and check the phone setup checklist and Accessibility service.

For future updates, use **Settings → About → Check for updates → Download and install**. Installation is available while protection is locked. Android may ask you to allow installations from Focused WhatsApp once. New installations start with protection off, no password, and a one-minute delay; existing settings are preserved when updating.

## This release

Google sign-in and Drive backup now use a separate Focused WhatsApp project instead of the previous shared project.

After updating, open Settings → Google backup, sign in again, allow hidden app storage, then choose Back up now to save this phone's current settings. Reconnecting alone does not upload settings or start scheduled backups.

Phone settings, protection on/off, passwords, waits, usage and backup schedule are preserved. Existing cloud copies remain untouched and are not imported automatically. Do not uninstall to update.

The app now has a public homepage and privacy policy for Google consent. Actual signed-phone consent and Drive backup/restore remain acceptance checks; synthetic tests do not establish those outcomes.

[App homepage](https://phoobarred.github.io/focused-whatsapp-updates/) · [Privacy policy](https://phoobarred.github.io/focused-whatsapp-updates/privacy.html)

## History and limitations

Earlier downloads and their notes remain in [Releases](https://github.com/phooBarred/focused-whatsapp-updates/releases). Screen recognition depends on the WhatsApp interface. Synthetic emulator tests do not establish real WhatsApp, Samsung, or Andoff compatibility. This is not a tamper-proof blocker.

The previously reported Google Play Protect harmful-app warning has not been resolved or proven fixed by this release. Blocking may briefly pause during installation; reopen the app afterward to check protection. Google sign-in, scheduled backups, and cross-install restore still require physical-device validation.

Screen content stays on the phone. Optional Google backup saves configuration only; it does not back up protection activation, waits, access sessions, today's usage, or phone permissions.

Account backups include a salted password verifier, never the plaintext password, messages, or screen content. New backups use Google Drive's hidden app storage with account/app access controls; they are not end-to-end encrypted. Copies made by version 0.7.4 or earlier remain in Firebase under its project administration and are not automatically imported or deleted. Android automatic backup is disabled. Signing out keeps local settings and the saved cloud copy. APKs contain no personal profile, saved password, lock state, or developer backup.
