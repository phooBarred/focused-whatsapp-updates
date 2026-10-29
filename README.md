# Focused WhatsApp downloads

[Download version 0.7.4](https://github.com/phooBarred/focused-whatsapp-updates/releases/download/v0.7.4/focused-whatsapp-0.7.4.apk) · [Release details](https://github.com/phooBarred/focused-whatsapp-updates/releases/tag/v0.7.4)

Focused WhatsApp is an experimental Android 12+ app for limiting WhatsApp Status and Channels. Chats and calls remain available. This repository contains public APK downloads; it is not the source repository.

Install the APK over the existing app; do not uninstall first. Android asks you to approve installation. Updates preserve settings and waits. Open the app afterward and check the phone setup checklist and Accessibility service.

For future updates, use **Settings → About → Check for updates → Download and install**. Installation is available while protection is locked. Android may ask you to allow installations from Focused WhatsApp once. New installations start with protection off, no password, and a one-minute delay; existing settings are preserved when updating.

## This release

Schedule and daily-allowance editing now follows your current unlock method directly from the editor.

- Edited allowance dialogs show green Save and red Cancel. Child edits stay in their draft until you save the parent schedule.
- Stronger plans apply immediately. In delay-enabled modes, saving a weaker plan starts the current wait or keeps an existing countdown; the change applies automatically when the wait finishes.
- Password-only mode asks for the existing password without sending you back to Focus. Password override can save immediately.
- Focus shows pending changes and lets you cancel them. Queued plans stay on the phone and are excluded from backups. Applying a plan does not turn protection off, open settings access, or refill daily usage.

Existing settings and waits are preserved. Install over the existing app; do not uninstall first.

Automated coverage includes wait deadlines, reboot and cancellation, password flows, saved-state migration, backup exclusion, stale editors, and Android 12 dialog interactions with normal and enlarged text. These emulator checks do not establish Samsung, Andoff, or real WhatsApp compatibility for every route. The previously reported Play Protect warning has not been proven fixed.

## History and limitations

Earlier downloads and their notes remain in [Releases](https://github.com/phooBarred/focused-whatsapp-updates/releases). Screen recognition depends on the WhatsApp interface. Synthetic emulator tests do not establish real WhatsApp, Samsung, or Andoff compatibility. This is not a tamper-proof blocker.

The previously reported Google Play Protect harmful-app warning has not been resolved or proven fixed by this release. Blocking may briefly pause during installation; reopen the app afterward to check protection. Google sign-in, scheduled backups, and cross-install restore still require physical-device validation.

Screen content stays on the phone. Optional Google backup saves configuration only; it does not back up protection activation, waits, access sessions, today's usage, or phone permissions.

Account backups include a salted password verifier, never the plaintext password, messages, or screen content. Access is restricted to the signed-in account, but backups are not end-to-end encrypted and database administrators can administer them. Android automatic backup is disabled. Signing out keeps local settings and the saved cloud copy. APKs contain no personal profile, saved password, lock state, or developer backup.
