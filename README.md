# TinyRec

A native macOS screen recorder, polished out of the box.
Cursor zoom, captions, voice over and a built-in editor — already on, on day one.

[**tinyrec.io**](https://tinyrec.io) · [**Download for macOS**](https://github.com/davidtran/tinyrec-release/releases/latest/download/TinyRec-Mac-arm64-Installer.dmg) · [Web editor](https://editor.tinyrec.io) · [@davidtranwd](https://x.com/davidtranwd)

---

This repository hosts the official **TinyRec** release builds. The app itself lives on its product site — this repo is just where the `.dmg` files are published. If you're looking to download, install, or get support, you're in the right place.

## Download

Always-current stable build (no version pinning needed — GitHub redirects this URL to the latest release):

- **Apple Silicon (M-series Macs):** [TinyRec-Mac-arm64-Installer.dmg](https://github.com/davidtran/tinyrec-release/releases/latest/download/TinyRec-Mac-arm64-Installer.dmg)

For older versions or release notes, see the [Releases page](https://github.com/davidtran/tinyrec-release/releases).

## Install

1. Download the `.dmg` above.
2. Open it and drag **TinyRec** into your `Applications` folder.
3. Launch it. The first run walks you through Screen Recording, Camera and Microphone permissions — about a minute.

If macOS Gatekeeper warns you on first launch, right-click the app and choose **Open** (the binary is signed and notarised — this prompt is standard for new users on a fresh download).

## Requirements

- macOS 13 (Ventura) or later
- Apple Silicon recommended (especially for 4K capture and export)
- Intel Macs supported

## What it does

- Native screen capture via **ScreenCaptureKit** at 60fps — no browser, no Electron quirks
- **Auto Zoom**: motion-tracked zoom and pan that follows your cursor, no keyframes
- **Captions**: Whisper transcribes your narration locally — no cloud upload, no per-minute charge
- **AI Voice Over**: type a script, get a natural voice track timed to your scenes
- **Camera overlay**: smooth full-screen-to-corner webcam intros
- **iPhone recording**: capture iPhone over USB, framed in a real device bezel
- **Annotations & masks**: arrows, highlights, blurs, spotlights — all animated
- **Timeline editor**: trim, reorder, change speed, cut silence
- **Rust render pipeline**: 4K exports typically run 2–3× faster than the source video
- **On-device, always**: recording, transcription and export run locally. Nothing leaves your Mac unless you share it yourself.

## Pricing

- **Free** — every feature, every length, every resolution. Exports include a small TinyRec watermark.
- **Lifetime ($79, one-time)** — removes the watermark, adds priority support, includes all future updates. No subscription.

Buy from [tinyrec.io/#pricing](https://tinyrec.io/#pricing).

## Privacy

TinyRec runs entirely on your Mac. There is no account, no cloud sync, no telemetry on your recordings. Captions are transcribed locally with Whisper. The app talks to the network only for update checks and your purchase activation.

## Support

- Email: [nam.trankhanh.vn@gmail.com](mailto:nam.trankhanh.vn@gmail.com)
- DM on X: [@davidtranwd](https://x.com/davidtranwd)
- Discord: [join the community](https://discord.gg/fV8SCzBnhS)
- Bug reports and feature requests: [open an issue](https://github.com/davidtran/tinyrec-release/issues)

I read every message.

## About

TinyRec is built by [Nam Tran](https://x.com/davidtranwd).

If you find a bug or want a feature, [open an issue](https://github.com/davidtran/tinyrec-release/issues) or reach out on X. The fastest way to influence what gets built is to ask.

---

© 2026 TinyRec. The source for this release lives in a private repository; binaries are published here under the standard end-user licence shipped inside the `.dmg`.
