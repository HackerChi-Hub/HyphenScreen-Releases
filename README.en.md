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

- **1.7.1** · Fixes the camera disappearing when cutout, blur or custom backgrounds process software-decoded recordings on Mac; existing media and edits are preserved.
- **1.7.0** · Export watermarks default to 黑粉录屏, can be disabled, and apply consistently to MP4 and GIF.
- **1.7.0** · Custom text, images or both, four editable examples, five positions, size and opacity controls, remembered on actual export.
- **1.6.9** · Eight local composition types cover evidence, processes, presenters, comparisons, metrics, checklists, timelines and structures without a model.
- **1.6.9** · Two palettes provide 16 actual 12-second example videos. Watch a type before editing your own content.
<!-- recent-features:end -->

**1.7.1：摄像头背景切换修复。** Mac上部分实际摄像头录制使用软件解码，切到抠图、模糊或自定义背景后人物可能消失。本版修复分割遮罩与视频帧的关联，保留现有素材、剪辑和分割模型；无需重录。Windows与Linux保留已公开的1.7.0，验证范围见本版发行说明。

**1.7.0: choose your export watermark.** Mac defaults to 黑粉录屏, with an off switch, custom text, local PNG/JPEG/WebP images or both. Four editable examples, five positions, size and opacity controls cover common uses; text adapts to the picture brightness. Settings are remembered on actual export, with one native overlay path for MP4 and GIF. No paid entitlement is active in this release. Windows/Linux 1.7.0 now include these watermark settings. Native and application CLI outputs were verified; desktop mouse-driven export remains unverified because macOS screen capture failed.

![Actual default, disabled, custom text and image watermark outputs](screenshots/export-watermark-170.jpg)

![Actual export-watermark component in an isolated browser test](screenshots/export-watermark-controls-170.png)

**1.6.9: eight local composition types with real video examples.** On Mac, choose source evidence, process, presenter, before/after comparison, metrics, checklist, timeline or structure. Two palettes provide 16 actual 12-second examples before editing content and timing, without a model. Presenter scenes use six complete illustrations of the same character, a shared explanation image and optional per-stage images. The narrow inspector uses two columns and a non-overlapping Apply area. Native image layers now decode WebP as well as PNG/JPEG. Windows and Linux 1.7.0 have now been built locally with these features. Fixed frameworks and six poses do not provide arbitrary character acting or story generation.

![Actual output from the eight local composition types](screenshots/local-explanation-eight-169.jpg)

![Actual stage image editing and save feedback](screenshots/presenter-content-169.jpg)

**1.6.8: content, actions and sounds share event timing.** On Mac, Create animation now offers Local composition for source evidence, processes and presenter actions without a model. The Content tab edits text, local images, steps and timing; actions and existing sounds use the same events. Animation can stay on the project ruler or follow one main recording clip, and consecutive compatible compositions reuse a track. Recomposition rebuilds controlled layers while retaining manually added layers. These are three fixed task frameworks, not a general skeleton or arbitrary-story generator. Windows and Linux 1.7.0 include these features.

![Actual local composition editor](screenshots/local-explanation-168.png)

![Actual content editing and timing controls](screenshots/content-editing-168.png)

**1.6.7: compact whole-video packaging on Mac.** One segment list combines thumbnails, titles, layouts and timing; the current layout is edited in a dropdown. The ten Chinese display names now have four characters, including Red Poster. Existing project IDs, visual styles and sounds remain compatible. A typical four-segment configuration fits at 1280×720; smaller windows and longer lists can scroll. Windows and Linux 1.7.0 include this interface update.

![Compact whole-video packaging editor](screenshots/packaging-167.jpg)

**1.6.6: whole-video packaging encoder fix for Windows and Linux.** Uses bundled OpenH264 instead of unavailable libx264, with no extra encoder installation. Mac now provides 1.7.0. See the download table and release notes for versions and verification scope.

**1.6.5: ten coordinated video packages.** Open a project and choose Whole-video packaging in the AI panel. Each package provides an opener, list, focus and metric layout, with real examples before editing. Generate 1–12 segments locally and add them together while retaining narration. Effects default on and music defaults off. Saved settings can regenerate and replace their original group, protecting manually edited clips. Generated clips are editable on the timeline; internal layers are not individually editable. Apple-silicon Mac testing covered all ten default palettes and real four-segment generation, seeking, playback and reopening. Other platforms follow the actual download table.

![HyphenScreen](screenshots/packaging-165.png)

**1.6.4: steadier cursor-follow zooms.** Select a zoom region and choose the steady or responsive focus mode. Small movements hold the composition; crossing the safe area starts a smooth pan. Consecutive clicks form one operation, and zoom-out holds the last focus. Recording cursor telemetry is required; external videos can use manual focus. Existing projects retain legacy follow. Version 1.6.4 is available on Mac, Windows and Linux. Checks covered real-recording playback and export on Apple Silicon Mac, a synthetic native export on Windows, and package installation on Ubuntu; desktop verification remains platform-specific.

![Camera follow settings](screenshots/camera-follow-164.png)

**1.6.3: find animation by purpose.** The library now has 230 entries across nine categories. Chapter titles, charts, terminals and other styles share purpose-based entries while existing assets and projects remain compatible. Chinese examples include statistical rings, terminal simulation, code typing and chat. Model tools also discover reference variants inside mixed-source families. These capabilities remain available in Mac 1.6.5 and Windows/Linux 1.6.6; see the download table for each package.

![HyphenScreen 1.6.3](screenshots/material-library-163.png)

<!-- development-timeline:start -->

**1.6.1: prevent doubled background music after timeline edits.** Preview stops stale programme audio before returning to live mixing; delayed playback requests recheck the current mode. Includes the animation-placement and lifted-recording fixes from the local-only 1.6.0 build. Platform versions are listed in the download table.

**1.6.0: keep animations at their timeline positions after jump cuts.** Entrance, exit and source-label overlays now map from the editor ruler to the actual source footage, preventing delayed flashes over later recordings in both preview and export. This fix is available on Mac; other platform versions are listed in the download table.

Recordings lifted into separate picture rows can move horizontally in absolute time without packing the main sequence back to the start or shifting other clips. Single-row main-track reordering is preserved.

**1.5.9: jump cuts, ripple deletion and compatible shared tracks.** Adjust a whole-clip jump-cut range; deleting a main recording shifts later independent visuals and audio. The editing API moves non-overlapping compatible objects into one track, rejecting locked, incompatible or conflicting targets. A private episode reduced 51 animation tracks to 3 while preserving content and overlap order. Playback recovery and player cleanup were improved; the reported long-session player failure was not reliably reproduced, so full resolution is not claimed.

**1.5.9: jump cuts and playback recovery.** Add Jump Cut selects the complete current clip and offers two range handles. Removing a main recording clip moves later independent items together. Playback can restart after a tail cut, and source-list changes preserve the active media by identity. See the source progress log for validation and release status.
<!-- style-preview-156:start -->

**1.5.8: preview animation projects directly.** Projects with native animation, voiceover and music now use the animation canvas rather than decoding an audio asset as video. Preview sources come from the actual picture timeline. The external editing interface also fixes scene input-schema compatibility. macOS development-editor seek and complete-playback checks passed; see release notes for installation and platform status.

**1.5.7: animation wait controls and live feedback.** A highlighted clock button sets total and no-output wait limits independently (1–360 minutes), remembered per engine. Explanation and storyboard text appear as received; supported parameter streams report scene structure progress, and every scene write reads back the actual layer count and duration. Steps remain expandable after completion. Subscription channels without argument deltas report actual stages only. Included in macOS 1.5.7; complete-story output quality still requires user review.
### Preview a style before creating an animation

All 19 styles now include a typical vector sample using the same Chinese title, “黑粉录屏”. Hover or focus with the keyboard to preview motion, click to select, then play or pause the larger example. Wide windows place content on the left and styles on the right; narrow windows use two columns. Selection and input persist across groups.

![Actual composer component with unified style samples](screenshots/animation-style-previews-dialog.png)

[View all 19 samples](screenshots/animation-style-previews-gallery.png). Captured from the real component in browser QA. These built-in samples explain visual styles; they are not model-generated results. Actual objects and actions still follow the user's explanation.

On macOS, a runtime hardware decode failure now tries software decoding for that source while restoring the playback position. Working hardware paths remain unchanged; no source transcoding or project edits are involved. Six-source native preview and failure recovery were checked; complete installed-desktop acceptance is not claimed.
<!-- style-preview-156:end -->

### 1.5.3: Fewer tracks, direct playback after edits

Move non-overlapping annotations, images, effects or animations into the center of a compatible track, or choose a destination from the context menu. Empty source tracks hide automatically. Drop at a track edge to change picture order; horizontal dragging still changes timing. New annotations reuse a visible, unlocked annotation track, with overlaps shown in rows. Locked, hidden or conflicting destinations reject the move.

Upper picture tracks still cover lower ones, while audio mixes independently. Only left headers collapse groups. Automatic captions render again in preview and export, and playback resumes after long cuts without changing pages. Real macOS desktop interactions and native media were checked; see the download table for each platform's available version.
<!-- development-timeline:end -->

<!-- development-animation-authoring:start -->
### 1.5.1: 19 methods for animation from an explanation

Open “Create animation” in the AI panel. Enter content and custom requirements, then choose from 19 methods grouped by clear explanations, playful illustration and spatial materials. Selection persists across groups. Set duration, placement or continuous scenes; the model reads one method on demand and designs objects, actions and shots as editable layers, keyframes and clips. Refined guidance calls for spatial depth, functional motion, secondary response and reading pauses. Standalone silent animation, transparent overlays and full-screen inserts require no placeholder video.

**Kimi verified in 1.5.3:** compatible endpoints no longer reject animation curve tool parameters with HTTP 400. The configured `k3-256k` actually generated an eight-second, fourteen-layer native scene with two custom Bézier keyframes; project insertion, readback and native export passed. Bring your own endpoint, model and key, test the tool round trip, then use Create animation. This is one verified run, not a claim that every model or style has passed.

![Exported frame from the actual Kimi-generated native scene: restore a record without changing the total](screenshots/kimi-native-153.png)

![1.5.1 composer component: 19 methods and custom requirements](screenshots/ai-animation-methods-151-component.png)

This screenshot shows the application's real composer component in a browser QA page. It demonstrates the interface, not a model-generation run or complete desktop acceptance.

LocalBrain discovers its loaded language model. A live Qwen3.8 27B test generated a custom scene, wrote tools, read the project back and passed native export. One eight-second paper deduplication scene took about 6 minutes 4 seconds to generate; this is a single observation, not a speed guarantee. Subscription models also generated paper routing, deduplication and a 2D continuous water-cycle scene. The 19 methods have not each passed model-generation quality review. True 3D, refraction and fluids require external production; reference films and privately authored showcases are not presented as in-app generation results.

“Test connection and tools” checks a real round trip using the current model and endpoint, without saving a test draft or modifying the project. A configured key does not mean authenticated. MiniMax candidates do not trigger automatic paid probes. Conversation messages and busy states are isolated; local two-chat and subscription concurrent switching were tested. Context is a conversation-text estimate, not total model usage.
<!-- development-animation-authoring:end -->

<!-- evergreen:demos:start -->
## ▶ Watch a practical demo

**Recording, cursor zoom, animation and AI-assisted speech editing**

| Bilibili | YouTube |
| :---: | :---: |
| [![Watch on Bilibili](https://img.shields.io/badge/Bilibili-00a1d6?style=for-the-badge&logo=bilibili&logoColor=white)](https://www.bilibili.com/video/BV1zGHe6UEgg/) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-ff0033?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=mJV1niXRbSs) |

These videos show the versions available when recorded. Use the current release information on this page for downloads and capabilities. Narration is in Chinese.
<!-- evergreen:demos:end -->

## Download: 1.7.1

| Platform | Package | SHA-256 |
|---|---|---|
| macOS 13+（Apple 芯片 arm64） | [Download HyphenScreen_1.7.1_arm64.dmg](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.7.1/HyphenScreen_1.7.1_arm64.dmg) | `6b6a1e592e5ffa7cd48170b653abd5c4df8c43f5154a856861fda3ff279fd18f` |
| Windows 10/11（x64）· 1.7.0 版 | [Download HyphenScreen_1.7.0_x64-setup.exe](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.7.0/HyphenScreen_1.7.0_x64-setup.exe) | `097c26bcfd919c306216d291f214b23761f98dd5d837a21870141eda035b79f6` |
| Linux（x86_64）· 1.7.0 版 | [Download HyphenScreen_1.7.0_x86_64.AppImage](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.7.0/HyphenScreen_1.7.0_x86_64.AppImage) | `c878a554f06cfa531d06822fe4dea6dc0f3e3510768abc6635e17379e7c8cfae` |
| Debian / Ubuntu（amd64）· 1.7.0 版 | [Download HyphenScreen_1.7.0_amd64.deb](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.7.0/HyphenScreen_1.7.0_amd64.deb) | `7e75be0fe1a2484f5fc5ac372b43c04ebde1d5004dbd0021e560fca544b095c4` |
| Arch Linux（x86_64）· 1.7.0 版 | [Download HyphenScreen_1.7.0_x64.pacman](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/download/v1.7.0/HyphenScreen_1.7.0_x64.pacman) | `87d98daba51dc893d621028aa61acf35612a8c5e1c87a82f8d9ae9f15f8bb52f` |

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

The unified Animation & Effects library has Common, Text & Titles, Data & Charts, Explanation, Brand & Outro, Social Platforms, Picture Effects, Hardware, AI Concepts and Flows & Architecture categories. It currently presents **230 grouped entry cards**, including **71 explanation cards** filtered by pointers, steps, comparisons and demonstrations. Similar styles share one card; 23 quote/statement examples form one text-title family. Short titles wrap, with original names still searchable.

There are 16 common built-in animation presets plus a social-card family covering 17 platforms. Another 380 reference migration previews are grouped by style, plus 300 native animations converted from LottieFiles free animations. These previews still need work on full source-parameter recalculation, complex filters and dynamic visual parity; they are not complete clones of every reference example.

Cross-source families include 13 chapter styles, 22 title styles, 10 people profiles, six quote cards, four progress rings and six terminal styles. Decorative icons remain separate from numeric charts. Sample text and URLs use Chinese HyphenTech examples; third-party licenses and provenance remain included.

![HyphenScreen 1.6.3](screenshots/material-text-163.png)

Social cards include Douyin, Kuaishou, Bilibili, Xiaohongshu, WeChat Channels, WeChat Official Accounts, WeChat, Weibo, Zhihu and Toutiao, plus YouTube, TikTok, Instagram, X, Facebook, LinkedIn and Twitch. Switching platform retains edited account text, titles and body content.

![Bilibili social card and the 17-platform selector](screenshots/social-platforms-110.png)

## Timeline, camera and audio

Split, move, trim or restore source content by dragging clip edges. Marquee-select and delete multiple visual objects with one undo. An expandable Visual group contains annotations, overlays and animation; empty tracks hide automatically. Familiar A/B, J/K/L, I/O, marker and frame-step controls sit alongside categorized context menus and wheel pan/zoom.

Camera layouts include picture-in-picture and horizontal/vertical split screens. Fullscreen camera intervals can cross video clips, with either a hard entry cut or a smooth transition. Adjust frame shape, border thickness/color and gradient pulse. Camera background blur, removal and replacement currently require macOS.

Audio tracks mix narration and music. Trim independently, detach source audio and set clip gain from -60 to +36 dB. Music ducking offers natural background, balanced narration and narration-first presets, with adjustable lead-in, hold and recovery. Local voice isolation currently requires macOS. Waveforms sample the visible interval, retaining source timing after cuts.

## Bring your own AI

![Subscription, local-model and API configuration](screenshots/ai-settings-110.png)

Codex and Claude subscription modes detect official local clients and sign-in state, with visible sign-in/re-authentication guidance; Codex has a login fallback. LocalBrain discovers the local service and connects to a preferred language model on demand. Availability follows actual service status and model responses, not a guarantee that every local model has been tested.

API options include Kimi subscription (endpoint and model pre-filled), OpenAI, Claude, Gemini, Mistral, OpenRouter, MiniMax, MiniMax Token Plan and OpenAI-compatible endpoints. Each provider keeps its own model and endpoint settings across switches. MiniMax domestic and international endpoints are configured separately. Recipes cover narration cleanup, pauses, filler words, repeats, voice processing, music ducking, zoom, redaction, portrait highlights and output checks. The current MCP interface exposes **92 tools** for implemented project, timeline, caption, audio, animation and export operations. Review AI edits in the preview.

## Export and project management

![MP4/GIF, resolution, frame rate and codec options](screenshots/export-110.png)

Export MP4 or GIF with selectable resolution, frame rate and H.264/H.265 encoding. “Upscale” indicates resizing beyond source dimensions; it does not recover missing source detail. Output checks inspect loudness, silence, black/frozen frames, duration and text boundaries. Automatic sensitive-text detection and OCR output readback currently require macOS; manual redaction is available across platforms.

**Export watermark:** Mac 1.7.0 defaults to 黑粉录屏 and offers off, custom text and local images. This applies to MP4 and GIF exports; normal editor previews remain unchanged. Windows/Linux 1.7.0 offer the same optional, customizable watermark settings.

Choose separate project, recording and cache directories, including external drives. Manage cache categories and restore named or automatic project-history checkpoints.

## Download, privacy and platform scope

The application is free to download without a HyphenScreen account. Subscription/API services require your own account, credentials and available quota. Recordings and projects stay on your computer; a cloud AI request sends the conversation and relevant project information to the selected service. Local-model inference can remain local. Anonymous device counting can be disabled.

- **macOS:** 13+, Apple Silicon; DMG, locally signed but not Apple-notarized.
- **Windows:** Windows 10/11 x64 with D3D11 video decoding; unsigned installer.
- **Linux:** x86_64, glibc 2.35+, Vulkan and desktop portals; AppImage, deb and pacman packages.

The 1.6.3 development editor passed purpose browsing, search, insertion and animation playback. Three cross-source style switches passed real API save and fresh-profile reopen checks. Individual source parameters retain their documented editing limits. Installation, package checks and public download verification are recorded in the release evidence; full recording, physical-camera and online-generation checks were not repeated. Windows/Linux desktop verification remains pending.

Copyright © 2026 HyphenTech. Required third-party licenses and original notices are included in the application. This public repository distributes packages and documentation; source remains private.
<!-- evergreen:capabilities:end -->

<!-- evergreen:discovery:start -->
## More HyphenTech software

[LocalBrain](https://github.com/HackerChi-Hub/localbrain-releases) · [HyphenScreen](https://github.com/HackerChi-Hub/HyphenScreen-Releases) · [ScreenLex](https://github.com/HackerChi-Hub/screenlex-download) · [HyphenBox](https://github.com/HackerChi-Hub/hyphenbox-release)
<!-- evergreen:discovery:end -->
