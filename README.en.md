<!-- evergreen:intro:start -->
![HyphenScreen · HyphenTech](screenshots/readme-hero.svg)

# HyphenScreen · Screen recording, editing and native animation

**Record the essential moments. Build the rest with images, animation and narration.**

HyphenScreen by HyphenTech is a desktop workspace for software tutorials, product demos and narrated videos. Record your screen, webcam and audio; edit multiple tracks; add captions and native motion graphics; then export a landscape or portrait video.


<p align="center"><a href="README.md">简体中文</a> | <a href="README.zh-TW.md">繁體中文</a> | <a href="README.en.md">English</a> | <a href="README.ja.md">日本語</a></p>

<p align="center"><a href="https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/latest"><img alt="Download" src="https://img.shields.io/badge/Download-18181b?style=for-the-badge&amp;logo=github" /></a> <a href="https://hyphentech.top"><img alt="Website" src="https://img.shields.io/badge/Website-334155?style=for-the-badge" /></a></p>
<!-- evergreen:intro:end -->

<!-- recent-features:start -->
## Recent features and improvements (5 items)

- **1.4.8** · Camera full-screen preview stays active across cuts without briefly exposing the screen recording.
- **1.4.7** · Face restoration reports loading, restoration, encoding and saving, with apply and restore feedback.
- **1.4.6** · Camera WebM restoration uses actual timestamps when frame-rate metadata is invalid.
- **1.4.5** · Face restoration uses a dedicated dialog and clear fidelity slider; closing it keeps the job running.
- **1.4.4** · Optional local face restoration supports short trials, comparison and restore; models and Python are separate.
<!-- recent-features:end -->

<!-- evergreen:demos:start -->
## ▶ Watch a practical demo

**Recording, cursor zoom, animation and AI-assisted speech editing**

| Bilibili | YouTube |
| :---: | :---: |
| [![Watch on Bilibili](https://img.shields.io/badge/Bilibili-00a1d6?style=for-the-badge&logo=bilibili&logoColor=white)](https://www.bilibili.com/video/BV1zGHe6UEgg/) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-ff0033?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=mJV1niXRbSs) |

These videos show the versions available when recorded. Use the current release information on this page for downloads and capabilities. Narration is in Chinese.
<!-- evergreen:demos:end -->

## Download: 1.4.8

| Platform | Package | SHA-256 |
|---|---|---|
| macOS 13+（Apple 芯片 arm64） | [Download HyphenScreen_1.4.8_arm64.dmg](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.4.8/HyphenScreen_1.4.8_arm64.dmg) | `fc2008c1d4254b6015664a45f2138245def1bf0d4486479a5e93cf8005e63874` |
| Windows 10/11（x64） | [Download HyphenScreen_1.4.8_x64-setup.exe](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.4.8/HyphenScreen_1.4.8_x64-setup.exe) | `c224abb68bb121b0b82c711e3e559a16473ad843b52f7311fcfdf83b30d09837` |
| Linux（x86_64） | [Download HyphenScreen_1.4.8_x86_64.AppImage](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.4.8/HyphenScreen_1.4.8_x86_64.AppImage) | `614580b3444b191891233fdf2e780105c8433a37809c9e0145528249f9c60eac` |
| Debian / Ubuntu（amd64） | [Download HyphenScreen_1.4.8_amd64.deb](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.4.8/HyphenScreen_1.4.8_amd64.deb) | `6b84244467df0c8c72b989e8dc9e940e05231bda2867b8e5e6b20fe24496c777` |
| Arch Linux（x86_64） | [Download HyphenScreen_1.4.8_x64.pacman](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.4.8/HyphenScreen_1.4.8_x64.pacman) | `1f3444ac63f0c6d90fd687aec18465a8c32ae052d15d32dc32b3c7cb359ab091` |

<!-- evergreen:capabilities:start -->
![Native animation editor, editable layers and the Visual timeline group](screenshots/animation-editor-110.png)

## A complete workflow

| Stage | Features |
|---|---|
| Capture | Screen/window/region recording, webcam, microphone, system audio, saved recording profiles and pointer tracking |
| Edit | Batch video/audio import, multiple video tracks with no fixed track limit, upper-layer picture compositing and mixed audio |
| Compose | Aspect-preserving frames, picture-in-picture, horizontal/vertical split layouts, fullscreen camera intervals and animated borders |
| Caption | Local transcription, manual text editing, search, styles, colors, backgrounds and Chinese line wrapping |
| Sound | Independent audio trimming and clip volume, EQ, compression, limiting and music ducking presets |
| Animate | Independent scenes, editable layers, keyframes, easing, duration, speed and playback modes |
| Assist | Subscription clients, local models, custom APIs, editing recipes and MCP tools |
| Deliver | MP4/GIF, resolution/frame-rate/codec options, portrait highlights, redaction and output checks |

## Independent native animation

Animation clips generate their own frames, including backgrounds, without a placeholder video. Combine a recorded intro with animated charts, images, video and imported TTS narration. Text, images, shapes, vector graphics, charts and arrows can form layers; edit their stacking, groups, position, size, opacity, rotation, color and supported numeric properties. Keyframes and easing describe motion.

Preview and export share Rust compositor scene logic. AI changes JSON scene data rather than running Remotion code. Drag objects in the preview or enter precise values. Set start time, duration and speed; choose play once, loop or hold the last frame. A static display option preserves existing keyframes for later use.

![Animation timing, speed and playback controls](screenshots/animation-timing-110.png)

## A library organized by purpose

The unified Animation & Effects library has Common, Text & Titles, Data & Charts, Explanation, Brand & Outro, Social Platforms, Picture Effects, Hardware, AI Concepts and Flows & Architecture categories. It currently presents **333 grouped entry cards**, including **108 explanation cards** filtered by pointers, steps, comparisons and demonstrations. Similar styles share one card; 23 quote/statement examples form one text-title family. Short titles wrap, with original names still searchable.

There are 16 common built-in animation presets plus a social-card family covering 17 platforms. Another 368 reference migration previews are grouped by style, plus 300 native animations converted from LottieFiles free animations. These previews still need work on full source-parameter recalculation, complex filters and dynamic visual parity; they are not complete clones of every reference example.

![Purpose filters and readable short titles in the current Chinese interface](screenshots/animation-library-110.png)

Social cards include Douyin, Kuaishou, Bilibili, Xiaohongshu, WeChat Channels, WeChat Official Accounts, WeChat, Weibo, Zhihu and Toutiao, plus YouTube, TikTok, Instagram, X, Facebook, LinkedIn and Twitch. Switching platform retains edited account text, titles and body content.

![Bilibili social card and the 17-platform selector](screenshots/social-platforms-110.png)

## Timeline, camera and audio

Split, move, trim or restore source content by dragging clip edges. Marquee-select and delete multiple visual objects with one undo. An expandable Visual group contains annotations, overlays and animation; empty tracks hide automatically. Familiar A/B, J/K/L, I/O, marker and frame-step controls sit alongside categorized context menus and wheel pan/zoom.

Camera layouts include picture-in-picture and horizontal/vertical split screens. Fullscreen camera intervals can cross video clips, with either a hard entry cut or a smooth transition. Adjust frame shape, border thickness/color and gradient pulse. Camera background blur, removal and replacement currently require macOS.

Audio tracks mix narration and music. Trim independently, detach source audio and set clip gain from -60 to +36 dB. Music ducking offers natural background, balanced narration and narration-first presets, with adjustable lead-in, hold and recovery. Local voice isolation currently requires macOS. Waveforms sample the visible interval, retaining source timing after cuts.

## Bring your own AI

![Subscription, local-model and API configuration](screenshots/ai-settings-110.png)

Codex and Claude subscription modes detect official local clients and sign-in state, with visible sign-in/re-authentication guidance; Codex has a login fallback. LocalBrain discovers the local service and connects to a preferred language model on demand. Availability follows actual service status and model responses, not a guarantee that every local model has been tested.

API options include OpenAI, Claude, Gemini, Mistral, OpenRouter, MiniMax, MiniMax Token Plan and OpenAI-compatible endpoints. MiniMax domestic and international endpoints are configured separately. Recipes cover narration cleanup, pauses, filler words, repeats, voice processing, music ducking, zoom, redaction, portrait highlights and output checks. The current MCP interface exposes **92 tools** for implemented project, timeline, caption, audio, animation and export operations. Review AI edits in the preview.

## Export and project management

![MP4/GIF, resolution, frame rate and codec options](screenshots/export-110.png)

Export MP4 or GIF with selectable resolution, frame rate and H.264/H.265 encoding. “Upscale” indicates resizing beyond source dimensions; it does not recover missing source detail. Output checks inspect loudness, silence, black/frozen frames, duration and text boundaries. Automatic sensitive-text detection and OCR output readback currently require macOS; manual redaction is available across platforms.

**Since 1.4.0:** exported videos and GIFs carry a small 黑粉科技 (HyphenTech) badge in the bottom-right corner — the brand mark plus the name, about 150×46 px in a 1080p frame, switching between light and dark lettering with the picture behind it. It marks files made with the app and cannot be turned off; the editor preview does not show it.

Choose separate project, recording and cache directories, including external drives. Manage cache categories and restore named or automatic project-history checkpoints.

## Download, privacy and platform scope

The application is free to download without a HyphenScreen account. Subscription/API services require your own account, credentials and available quota. Recordings and projects stay on your computer; a cloud AI request sends the conversation and relevant project information to the selected service. Local-model inference can remain local. Anonymous device counting can be disabled.

- **macOS:** 13+, Apple Silicon; DMG, locally signed but not Apple-notarized.
- **Windows:** Windows 10/11 x64 with D3D11 video decoding; unsigned installer.
- **Linux:** x86_64, glibc 2.35+, Vulkan and desktop portals; AppImage, deb and pacman packages.

Download instructions and SHA-256 values are on the [main download page](https://github.com/HackerChi-Hub/HyphenScreen-Releases). Check for updates through the application menu or download the current package. Mac 1.4.5 matches all 427 files and links with a valid local signature. Real desktop checks passed the single-button dialog, visible fidelity handle, adjustment from 70% to 85%, background processing after closing, apply, playback and restore. The installed API also processed and exported a clip with identical decoded audio. This was a focused interface check, not a repeated full capture or webcam checklist. Windows/Linux desktop and face-restoration hardware checks remain pending. Region selection is available on macOS/Windows. Animation/settings/export images come from the 1.1.0 macOS demo in Chinese. Private face-restoration screenshots are not published.

Copyright © 2026 HyphenTech. Required third-party licenses and original notices are included in the application. This public repository distributes packages and documentation; source remains private.
<!-- evergreen:capabilities:end -->

<!-- evergreen:discovery:start -->
## More HyphenTech software

[LocalBrain](https://github.com/HackerChi-Hub/localbrain-releases) · [HyphenScreen](https://github.com/HackerChi-Hub/HyphenScreen-Releases) · [ScreenLex](https://github.com/HackerChi-Hub/screenlex-download) · [HyphenBox](https://github.com/HackerChi-Hub/hyphenbox-release)
<!-- evergreen:discovery:end -->
