---
title: Privacy Policy
---

# Privacy Policy for Cartridge

**Last updated: 6 May 2026**

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
- **Apple Music access** (optional, opt-in): Used in two ways: (1) to fetch artist images and album artwork from the Apple Music catalog when your NAS does not have cover art, and (2) if you enable it in Settings, to add the currently-playing track from your NAS to your Apple Music library, favorites, or a playlist you choose. Only the album title, artist name, and track title are sent to Apple Music — no listening history, library contents, play counts, or other personal information is shared. Adding tracks requires an active Apple Music subscription. You can deny this permission, or leave streaming integration disabled in Cartridge's Settings, and the app will continue to work normally with placeholder artwork and no streaming-service integration.
- **Background audio**: Allows music playback to continue when the app is in the background or the screen is locked.

## Third-party services

The only external services Cartridge communicates with are:

1. **Your own Synology NAS**: Direct connections to browse and stream your music library.
2. **Apple Music catalog** (via MusicKit, optional): Used to look up artist images and missing album artwork, and — if you enable streaming integration in Settings — to add tracks from your NAS to your Apple Music library, favorites, or a playlist you choose. Only artist names, album titles, and (for adds) track titles are sent. Adding tracks requires an active Apple Music subscription. Requires your permission (iOS will prompt you on first use).
3. **DNS resolution**: Via iOS system services.
4. **Synology QuickConnect** (optional): Relay connections through Synology's own QuickConnect infrastructure when a direct connection is not possible. Subject to [Synology's privacy policy](https://www.synology.com/en-global/company/legal/privacy).
5. **Spotify** (optional, advanced): If you enable Spotify integration in Settings, Cartridge can add tracks from your NAS to your Spotify Liked Songs or a playlist you choose. To use this feature you create your own free Spotify Developer App, paste its clientId into Cartridge's Settings, and authenticate via the standard Spotify OAuth flow. **As of 9 March 2026, Spotify requires you to have an active Spotify Premium subscription to use this feature, and limits each developer to one App with up to five authorised users — this is a Spotify policy that Cartridge cannot work around.** Track title and artist are sent to Spotify's catalog to find a match. Your Spotify access tokens are stored in the iOS Keychain on your device only and never sent to the developer. The clientId you paste is stored in the app's local preferences. Subject to [Spotify's privacy policy](https://www.spotify.com/legal/privacy-policy/).

Cartridge contains no third-party tracking, analytics, or advertising SDKs.

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

For any questions about privacy or this policy, contact: **mbjprod@gmail.com**
