---
title: Support
---

# Cartridge — Support

**Cartridge** is an independent, unofficial music player for Synology Audio Station. This page answers common questions and provides a way to get in touch.

## Contact

For bug reports, feature requests, or general questions:

📧 **mbjprod@gmail.com**

When reporting a bug, it really helps to include:

- The version of Cartridge (visible in **Settings → About**)
- Your iPhone or iPad model and iOS version
- Your Synology NAS model and DSM version
- A description of what you were doing and what went wrong
- Any error messages shown in the app

## Frequently asked questions

### What is Cartridge?

Cartridge is a third-party music player for your Synology NAS. It connects to Audio Station on your NAS and lets you browse and stream your music library with high-quality audio playback, gapless playback, AirPlay support, and offline downloads.

Cartridge is **not** made by or affiliated with Synology Inc. It is an independent app built by a single developer.

### What do I need to use Cartridge?

- An iPhone or iPad running iOS 17 or later
- A Synology NAS running DSM 7 or later, with the **Audio Station** package installed
- A Synology account on the NAS with permission to access Audio Station
- Your music library organized in Audio Station

### How do I connect to my NAS?

On first launch, tap **Connect to Server** and enter:

- **Address**: Your QuickConnect ID, your DDNS hostname, or your NAS's IP address (with port if needed)
- **Username** and **Password** for your Synology account
- **2FA code** if your account has two-factor authentication enabled

The app will try to reach your NAS via the fastest available path: local IP, QuickConnect, DDNS, or QuickConnect relay.

### Does Cartridge work over the internet?

Yes. If your NAS is reachable via QuickConnect or a public address (DDNS), Cartridge can connect to it from anywhere. The app will prefer the fastest available connection: local network first, then direct internet, then QuickConnect relay as a fallback.

### Why does the app ask for local network permission?

iOS 14 and later require apps to ask for permission before accessing other devices on your Wi-Fi network. Cartridge needs this permission to discover your NAS by IP address on your local network. Without it, local connections will fail silently.

### My NAS has a self-signed certificate. Will Cartridge work?

Yes. Cartridge includes a custom certificate trust handler that accepts self-signed certificates from your NAS. If your NAS has a valid certificate (for example, a Let's Encrypt certificate obtained through DSM), Cartridge will use it directly, which also enables full AirPlay support with lock-screen album art and rich metadata handoff to AirPlay receivers.

### Does Cartridge support FLAC, ALAC, DSD, and other lossless formats?

Yes. Cartridge supports MP3, AAC, M4A, ALAC, FLAC, WAV, AIFF, and DSD (DSF and DFF files). DSD files are decoded to high-quality PCM inside the app for playback over any audio output, including AirPlay, USB DACs, and Bluetooth.

### Does it support AirPlay?

Yes. Cartridge supports AirPlay 2 to any compatible receiver. When your NAS uses a valid (non-self-signed) certificate, AirPlay uses full URL handoff mode, which enables lock-screen metadata, album art, and full-screen receiver UI on devices like Apple TV and iMac.

For DSD files, audio streams to AirPlay receivers as decoded PCM frames. Some AirPlay-specific features (lock-screen art, full-screen receiver UI) are not available for DSD due to iOS limitations on audio engine-based playback.

### Does Cartridge collect my data?

No. Cartridge does not collect, transmit, or share any personal data with the developer or any third party. All data stays on your device and on your own NAS. See the [Privacy Policy](./privacy.html) for details.

### Is Cartridge open source?

[If applicable, link to the source repo. If not, remove this section.]

### How do I reset the connection?

Go to **Settings → Server → Reset Connection**. This clears all saved credentials and cached connection data. You'll need to enter your server address and log in again afterward.

### Why can't I share playlists with friends or create accounts?

Cartridge is a pure playback app. It does not have social features, user accounts, cloud sync, or sharing. Playlists and liked songs are stored locally on your device only.

## Known limitations

- Apple TV AirPlay transport controls (next/previous track) may not work in all configurations
- Very old DSM versions (pre-DSM 7) may have authentication issues due to API differences
- Subsonic protocol is not supported — Cartridge only talks to the native Synology Audio Station API
- Multichannel DSD may not deliver Spatial Audio to AirPods Pro (iOS limitation on audio-engine playback)

## Legal

Cartridge is an independent, unofficial app. "Synology", "Audio Station", and "DiskStation" are trademarks of Synology Inc. Cartridge is not affiliated with, endorsed by, or sponsored by Synology Inc.

© 2026 mbjprod. All rights reserved.
