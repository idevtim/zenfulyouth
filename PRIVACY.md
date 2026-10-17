# Privacy Policy

**Effective date:** October 17, 2026

Zenful Youth is a meditation app for every age, and it is designed to keep what you share with it on your device.

## Data Collection

Zenful Youth does **not** collect personal data, and we (the developer) never receive anything you do in the app. Specifically:

- **No accounts.** There is no sign-up, login, or user profile of any kind.
- **No analytics or tracking.** We don't use any analytics frameworks, tracking pixels, or advertising.
- **No servers of our own.** The app has no backend; nothing you type, say, or save is sent to us.

## How Meditations Are Written

Meditations are written by Apple Intelligence using the on-device model on your iPhone or iPad. What you type or pick to start a meditation is processed on your device and is not sent to us or to anyone else for writing.

## Spoken Voices (ElevenLabs)

Spoken meditations are optional. If you connect an ElevenLabs key, the text of each meditation is sent from your device directly to [ElevenLabs](https://elevenlabs.io) so it can be read aloud, using your own key and your own ElevenLabs account. The meditation may mention the topic you started it with. The app also uses your key to check that it works and how much of your monthly ElevenLabs allowance is left.

ElevenLabs handles that text under its own [Privacy Policy](https://elevenlabs.io/privacy-policy) and terms, including its own age requirements for account holders.

If you don't connect a key, nothing is sent to ElevenLabs: meditations are shown as on-screen text over the background sound instead.

## Speaking Instead of Typing

If you tap the microphone to say what's on your mind, Zenful Youth uses Apple's speech recognition to turn it into text. Where your device supports it, this happens entirely on the device; otherwise Apple processes it under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). The microphone is only used while you're dictating.

## On-Device Storage

Everything the app keeps stays on your device:

- **Your sessions:** topics, the meditation text, recordings of voiced sessions, how you felt afterwards, reflections, favorites, and where you stopped. Stored with SwiftData and in the app's Documents folder.
- **Your settings:** default length, voice and background sound, the daily reminder time, and the topics you picked during the welcome. Stored with SwiftData and UserDefaults.
- **Your ElevenLabs key:** stored in the iOS Keychain, readable only by Zenful Youth.

This data is included in your device's own backups (for example iCloud Backup, if you use it), like other app data. It is not accessible to us.

## Reminders and Live Activities

The daily reminder is a notification scheduled on your device; no push service is involved. The Live Activity showing how long is left in a session is also created on your device.

## Deleting Your Data

- Delete a single session from **Sessions** (swipe, or use the session's menu).
- Remove your ElevenLabs key from **Settings › Voice › Disconnect voice**.
- Deleting the app removes all of its data from your device.

## Children's Privacy

Zenful Youth is a general-audience app and is not directed at children. It does not collect personal information from anyone, including children under 13. Because nothing is sent to us, there is nothing for us to store, share, or delete. The only data that can leave the device is meditation text sent to ElevenLabs when a key is connected, as described above.

## Changes to This Policy

If this policy changes, we will update this page and the effective date above.

## Contact

If you have questions about this policy, [open an issue](https://github.com/idevtim/zenfulyouth/issues) on GitHub.
