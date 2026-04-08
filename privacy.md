---
title: Privacy Policy
---

# Privacy Policy for Cartridge

**Last updated: 8 April 2026**

Thank you for using Cartridge. This privacy policy explains what data the app handles, where it goes, and what control you have over it.

**Summary**: Cartridge does not collect, transmit, or share any personal data with the developer or any third party. Everything stays on your device and on your own Synology NAS.

## Who we are

Cartridge is an independent, unofficial music player for Synology Audio Station, developed by **mbjprod**. Cartridge is not affiliated with, endorsed by, or sponsored by Synology Inc. "Synology" and "Audio Station" are trademarks of Synology Inc.

Contact: **mbjprod@gmail.com**

## What Cartridge does

Cartridge lets you browse and play music stored on your own Synology Network Attached Storage (NAS) device. It connects directly from your iPhone or iPad to your NAS over your local Wi-Fi network or the internet. The developer does not operate any server that sits between you and your NAS.

## What data Cartridge handles

### Data stored only on your device

- **NAS connection details**: Your QuickConnect ID, DDNS address, or IP address, your username, and your password are stored securely in the iOS Keychain so you don't have to re-enter them on every launch.
- **Cached library data**: Album, artist, playlist, and song metadata fetched from your NAS are cached locally in the app's sandboxed storage to make browsing faster.
- **Cover artwork cache**: Images fetched from your NAS are cached in the app's sandboxed storage.
- **Downloaded music**: When you explicitly choose to download a song for offline listening, the audio file is stored in the app's sandboxed storage.
- **Play history and preferences**: Play counts, liked songs, search history, playlists, and app settings are stored locally using iOS UserDefaults and SwiftData.

**None of this data is transmitted to the developer or any third party.** It exists only on your device and is deleted when you uninstall the app.

### Data sent to your NAS

When you use Cartridge, the app sends the following to your own Synology NAS:

- Your login credentials (username, password, optional 2FA code) to authenticate
- API requests to browse your music library
- Requests to stream or download audio files and cover art

This traffic goes directly between your device and your NAS. It does not pass through any servers operated by the developer.

### Data NOT collected

Cartridge does not collect, store, or transmit any of the following:

- Your name, email address, phone number, or location
- Advertising identifiers (IDFA) or device identifiers
- Analytics or usage telemetry
- Crash reports (no third-party crash reporting SDK is integrated)
- Any contact information
- Any health, financial, or biometric data

Cartridge contains no third-party tracking, analytics, or advertising SDKs of any kind.

## Permissions the app requests

- **Local network access** (iOS 14+): Required to discover your Synology NAS on your Wi-Fi network and establish a direct connection. You will be prompted the first time the app tries to connect to a local address.
- **Background audio**: Allows music playback to continue when the app is in the background or the screen is locked.

## Third-party services

Cartridge does not integrate any third-party services, SDKs, analytics, advertising networks, or cloud services. The only network traffic the app generates is:

1. Direct connections to your own Synology NAS
2. DNS resolution via iOS system services
3. Optional QuickConnect relay connections through Synology's own QuickConnect infrastructure, which routes traffic between your device and your NAS when a direct connection is not possible. QuickConnect is a Synology service subject to [Synology's privacy policy](https://www.synology.com/en-global/company/legal/privacy).

## Children's privacy

Cartridge does not knowingly collect any information from children under 13. Because the app does not collect any data at all, no special provisions for children are necessary.

## Your rights and control

Because all data stays on your device:

- **To delete all app data**: Uninstall Cartridge from your device.
- **To disconnect from your NAS**: Open **Settings → Server → Disconnect** or **Reset Connection**.
- **To clear cached data**: Use the cache controls in the app's settings.

## Changes to this policy

If this privacy policy is updated, the "Last updated" date at the top of this page will change. Material changes will be announced in the app's release notes on the App Store.

## Contact

For any questions about privacy or this policy, contact: **[your email here]**
