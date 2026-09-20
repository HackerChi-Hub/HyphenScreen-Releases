# HyphenScreen

[简体中文](README.md) · [繁體中文](README.zh-TW.md) · **English** · [日本語](README.ja.md)

**Record your screen, edit your story, and finish in one desktop app.** HyphenScreen by HyphenTech brings screen capture, camera layouts, multitrack editing, captions and AI-assisted editing together for tutorials, product demos and narrated videos.

## Download

[Download installers and release notes](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases) · [Current platform versions and checksums](README.md#下载)

This is a preview release. The download table is the authority for each platform's current version; older Windows/Linux packages may not include the latest macOS features. Installers are public; the product's source repository remains private. There is no in-app automatic updater.

## What you can do

| Workflow | Features |
|---|---|
| Capture | Record a screen or window with microphone, system sound and camera. Save recording presets. Region capture is available on macOS and Windows. |
| Edit multiple sources | Import several video and audio files. Add video tracks without a fixed track-count limit. The upper visible video covers lower layers; audio is mixed together. |
| Fine editing | Move, split, duplicate and delete clips; trim or restore their source range with edge handles. Shift enables fine dragging, and arrow keys adjust a focused handle by a frame. |
| Organize layers | Rename, reorder, hide, mute and lock video tracks. Hiding the picture and muting its sound are independent. |
| Watch and check | Fullscreen preview (F to enter, Esc to leave) with a transport that fades out on its own. Pick a preview resolution — full, 3/4, 1/2, 1/3, 1/4 — so a heavy project plays smoothly; exports stay at full resolution. |
| Read the sound | The timeline waveform is drawn for the part of a clip you can actually see, at device-pixel detail: zooming in makes it finer instead of blockier, down to 4 ms per bar. |
| Screen and camera | Picture-in-picture, horizontal or vertical split screen, camera fullscreen, background options and customizable camera borders. Preserve the screen's aspect ratio inside a frame. |
| Captions and graphics | Local transcription, editable captions, styles, titles, annotations, zoom and categorized visual templates. |
| Sound | Independent clip levels, audio trimming, voice processing and music ducking with adjustable timing. Neural voice isolation is currently macOS-only. |
| AI assistance | Use a configured local model or the supported Codex login integration for editing tools and task templates. Results depend on the selected model and should be reviewed. |
| Finish | Export MP4 or GIF; inspect the finished file for issues such as silence, black frames and caption overflow. |

Track count has no fixed software cap; practical capacity depends on the device, media and effects. Multitrack picture priority is full-frame replacement, not simultaneous transparent layer compositing.

## A short workflow

1. Record a take, or import your videos and audio.
2. Add a video track, place supporting footage above the main recording, and trim its edges.
3. Edit captions, adjust voice and music levels, then preview the complete timeline.
4. Export and review the finished video before publishing.

## Interface tour

![Version 0.4.32: layered video editing, edge trimming and independent audio, shown with purpose-made demo media](screenshots/multitrack-0432.png)

![Recording controls](screenshots/recording.jpg)

![Timeline and editing workspace — earlier interface reference](screenshots/timeline.jpg)

![Camera layouts](screenshots/camera-layout.jpg)

![Voice processing and music ducking](screenshots/audio.jpg)

The first screenshot shows version 0.4.32; the remaining screenshots are interface references from earlier releases. See the Chinese release notes for version-specific changes.

## Requirements and privacy

- **macOS:** 13 or later, Apple silicon. Locally signed, not Apple-notarized.
- **Windows:** Windows 10/11 x64 with D3D11 hardware video decoding. Installer is unsigned.
- **Linux:** x86_64, glibc 2.35 or later, Vulkan and the appropriate desktop portal backend. AppImage needs FUSE 2.
- Recording, editing and export run locally. When you use AI chat, the conversation and relevant project text go to the provider you choose. Optional anonymous usage counting can be disabled in the app menu.
- Required third-party license notices are included in the application package.

© 2026 HyphenTech. HyphenScreen.
