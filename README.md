# Focused WhatsApp downloads

[Download version 0.7.3](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.7.3/focused-whatsapp-0.7.3.apk) · [Release details](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.7.3)

Focused WhatsApp is an experimental Android 12+ app for limiting WhatsApp Status and Channels. Chats and calls remain available. This repository contains public APK downloads; it is not the source repository.

Install the APK over the existing app; do not uninstall first. Android asks you to approve installation. Updates preserve settings and waits. Open the app afterward and check the phone setup checklist and Accessibility service.

For future updates, use **Settings → About → Check for updates → Download and install**. Installation is available while protection is locked. Android may ask you to allow installations from Focused WhatsApp once. New installations start with protection off, no password, and a one-minute delay; existing settings are preserved when updating.

## This release

Adds targeted detection for a direct Channel reader showing the Follow footer. The rule uses the relationship between visible controls observed in WhatsApp 2.26.41.77, without matching message text or blocking all conversations.

Regression tests cover the detected layout, ordinary chats, forwarded Channel cards and hidden controls. Both WhatsApp package names are covered by synthetic tests and emulator fixtures. The reported phone bypass still needs confirmation with this update; followed Channels and other layouts without this footer remain unverified.

Existing protection settings, schedules, daily allowances, passwords and waits are preserved. Install over the existing app; do not uninstall first.

## History and limitations

Earlier downloads and their notes remain in [Releases](https://github.com/phooBarred/focused-whatsapp-updates/releases). Screen recognition depends on the WhatsApp interface. Synthetic emulator tests do not establish real WhatsApp, Samsung, or Andoff compatibility. This is not a tamper-proof blocker.

The previously reported Google Play Protect harmful-app warning has not been resolved or proven fixed by this release. Blocking may briefly pause during installation; reopen the app afterward to check protection. Google sign-in, scheduled backups, and cross-install restore still require physical-device validation.

Screen content stays on the phone. Optional Google backup saves configuration only; it does not back up protection activation, waits, access sessions, today's usage, or phone permissions.

Account backups include a salted password verifier, never the plaintext password, messages, or screen content. Access is restricted to the signed-in account, but backups are not end-to-end encrypted and database administrators can administer them. Android automatic backup is disabled. Signing out keeps local settings and the saved cloud copy. APKs contain no personal profile, saved password, lock state, or developer backup.
