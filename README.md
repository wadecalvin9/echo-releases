<div align="center">

<img src="assets/icon.png" width="120" height="120" alt="Echo Icon" style="border-radius: 24px;" />

# Echo

### Pure-Rust Desktop & Lightweight Android YouTube Music & Local Audio Player

[![Latest Release](https://img.shields.io/github/v/release/wadecalvin9/echo-releases?style=for-the-badge&logo=github&color=30363D&logoColor=white)](https://github.com/wadecalvin9/echo-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20x64-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/wadecalvin9/echo-releases/releases/latest)
[![Android](https://img.shields.io/badge/Platform-Android%207.0%2B-2E7D32?style=for-the-badge&logo=android&logoColor=white)](https://github.com/wadecalvin9/echo-releases/releases/latest)
[![License](https://img.shields.io/badge/License-GPL%203.0-blue?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Creator](https://img.shields.io/badge/Creator-wadecalvin9-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/wadecalvin9)

<p align="center">
  <a href="#downloads"><b>[ Downloads ]</b></a> •
  <a href="#desktop-screenshots">Screenshots</a> •
  <a href="#features">Features</a> •
  <a href="#about--creator">Creator</a>
</p>

</div>

---

## Overview

**Echo** is a modernized, distraction-free music player ecosystem tailored for streaming YouTube Music and playing your personal offline music library. Available as a high-performance **Desktop application (Windows x64)** written in pure Rust (Iced + Tokio + Symphonia) and as a battery-efficient **Android application**.

No accounts mandatory. No tracking. No advertisements. Just instant, bit-perfect music.

---

## Desktop Screenshots

<div align="center">

### Home & Discover
<img src="assets/screenshot_home.jpg" width="95%" alt="Echo Desktop - Home & Discover" />

<br/><br/>

### Now Playing & Queue
<img src="assets/screenshot_nowplaying.jpg" width="95%" alt="Echo Desktop - Now Playing & Queue" />

<br/><br/>

### Cinema Synced Lyrics Stage
<img src="assets/screenshot_lyrics.jpg" width="95%" alt="Echo Desktop - Cinema Synced Lyrics Stage" />

<br/><br/>

### Artist Discography & Top Songs
<img src="assets/screenshot_artist.jpg" width="95%" alt="Echo Desktop - Artist Detail Page" />

</div>

---

## Downloads

### Latest Releases

| Package | Platform | Details | Download Link |
| :--- | :--- | :--- | :--- |
| **Echo Desktop (Windows x64)** | Windows 10 / 11 (64-bit) | Portable zip with `echo-app.exe` & `echo-auth.exe` helper | **[Echo-Desktop-Windows-x64.zip](https://github.com/wadecalvin9/echo-releases/releases/latest)** |
| **Echo Android (Universal APK)** | Android 7.0+ (API 24+) | Supports `arm64-v8a`, `armeabi-v7a`, `x86`, `x86_64` | **[Echo-1.0.3-core-release-4.apk](https://github.com/wadecalvin9/echo-releases/releases/download/v1.0.3/Echo-1.0.3-core-release-4.apk)** |

### Desktop Quick Start:
1. Download **`Echo-Desktop-Windows-x64.zip`** from the link above.
2. Extract the archive into any folder of your choice.
3. Run **`echo-app.exe`** to start streaming music immediately!

---

## Features

### Echo Desktop (Windows x64)
- **Spotify Desktop-Style Navigation:** Dedicated circular Home button alongside a capsule search bar with embedded Explore/Browse icon.
- **Pure Rust Audio Pipeline:** Symphonia + CPAL engine with Echo loudness leveling (`-3 dB` reference), `+12 dB` soft-clipped limiter, 10-band custom graphic EQ, and Harman AutoEQ headphone profiles.
- **Cinema-Style Synced Lyrics Stage:** Live synchronized lyrics from LRCLIB, KuGou, and Better Lyrics (TTML), click-to-seek, auto-scroll, romanization, and audio waveform strip.
- **Song Recognition (Shazam / SongRec):** 16 kHz mono audio fingerprinting via **WASAPI loopback** or microphone to recognize music playing anywhere on your PC.
- **Offline Downloads & Local Library:** Disk LRU stream cache, offline download manager, and local audio folder indexing (`lofty` tags).
- **Frameless Reactive Dark Theme:** Custom titlebar, minimize/maximize/close, and dynamic album-art colors (`Dynamic`, `Dark`, `OLED Black`).
- **Integrations:** Last.fm scrobbling, Windows System Media Transport Controls (SMTC), and taskbar playback progress.

### Echo for Android
- **Ultra-Fast Cold Start:** Launches immediately into your music without modal popups or onboarding hurdles.
- **MiniPlayer Gestures:** Natural swipe gestures with elastic resistance to skip tracks.
- **True Black OLED Mode:** High-contrast zinc/charcoal dark palette optimized for battery efficiency.
- **Multi-Provider Synced Lyrics:** Live time-synced lyrics with automatic fallback.
- **In-App Updater:** Automatic update notifications and one-tap in-app installation.

---

## About & Creator

- **Lead Developer & Creator:** [wadecalvin9](https://github.com/wadecalvin9)
- **Desktop Repository:** [Echo-desktop](https://github.com/wadecalvin9/Echo-desktop)
- **Releases Repository:** [echo-releases](https://github.com/wadecalvin9/echo-releases)
- **License:** GNU General Public License v3.0 (GPL-3.0-or-later)

---

<div align="center">
  <sub>Built with ❤️ by wadecalvin9 for music enthusiasts worldwide.</sub>
</div>
