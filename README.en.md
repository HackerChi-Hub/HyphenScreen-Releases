# HyphenScreen · Screen recording, editing and native animation

> 1.4.4 adds optional local face restoration under Clip Effects: try the first five seconds, compare, process and apply, or restore the original. CodeFormer models and Python are separate from the installer; portrait reconstruction is excluded. Automatic GPU/CPU selection falls back to CPU on accelerator errors. Apple MPS and CPU have been tested; CUDA/compatible ROCm paths still need corresponding hardware verification. Original audio, dimensions, frame rate and timing are retained. Check a short trial for natural results. Platform availability is shown on the download page; older screenshots do not depict this new panel.

> 1.4.3: selected images can sit below animations as backgrounds or above them as overlays. Existing projects retain their original order. Style changes preserve complete image timing, and deliberate base-video cuts no longer become silent black gaps in projects with animation tracks. This is image/animation stacking, not arbitrary reordering of all video layers.

> New in 1.4.2: marquee-selected video, audio, animation and visual effects move together when you drag a selected item's body. Relative timing, duration and track assignment stay intact; one undo restores the whole selection. Edge handles still trim individual items.

> New in 1.4.1: macOS recording audio feedback, synchronized webcam frames/mattes, and Android USB camera detection with unified front/rear lens selection and 0°/90°/180°/270° rotation. Android 12+, USB debugging authorization and local connection tools are required. Xiaomi 13 live preview at 1080p/30 fps, 90° preview rotation, and a short recording with pause/resume/save have been verified. Long recordings, rotated recording files, and cross-platform device tests remain pending. These camera features were introduced in 1.4.1; see the repository progress log for verification limits.

**Record the essential moments. Build the rest with images, animation and narration.**

HyphenScreen by HyphenTech is a desktop workspace for software tutorials, product demos and narrated videos. Record your screen, webcam and audio; edit multiple tracks; add captions and native motion graphics; then export a landscape or portrait video.

**Current release: [1.4.4](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/tag/v1.4.4)** · [Downloads](https://github.com/HackerChi-Hub/HyphenScreen-Releases) · [HyphenTech](https://hyphentech.top)

**New in 1.4.0:** 246 more library animations (914 in all, 333 entry cards): hardware devices plus six new directions — AI concepts, flows and architecture diagrams, screen-recording callouts (including a live magnifier that really enlarges the recording, in preview and export alike), benchmark charts whose bars, needles and ranks follow the numbers you type, HyphenTech brand packaging and emphasis accents. All new scenes are drawn natively with editable text and numeric parameters; terminal and code lines use the bundled JetBrains Mono. 35 hard-to-see or placeholder-logo entries were redrawn; old projects keep opening and exporting exactly as before. Animations with glow, soft shadows or outlines preview and export much faster with pixel-identical output (every new scene exports above 55 fps at 1080p; the slowest was 0.5 fps before), and an API-mode export that is interrupted no longer leaves a 0-byte file.

**New in 1.3.0:** 300 new editable native animations converted from LottieFiles free animations — likes and subscribe prompts, success states, loaders, arrows and gestures, hand-drawn emphasis, confetti, chat bubbles, tech icons, charts, transitions and abstract motion. Each passed the same frame-by-frame visual check as the rest of the library.

**New in 1.2.1:** very large frame-by-frame animations now play smoothly in the preview — frames ahead of the playhead are drawn in the background and the cache keeps a stable share when an animation is too big for it. Exported frames are unchanged.

**New in 1.2.0:** animations load, preview and edit much faster — projects with large animations open about 9× faster and edits show about 15× sooner; exported frames are unchanged. The project format is upgraded: older projects are converted on first open and a `.pre-v10.bak` backup is kept beside the original. Projects saved by 1.2.0 cannot be opened by older versions.

[简体中文](README.md) · [繁體中文](README.zh-TW.md) · English · [日本語](README.ja.md)

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

Download instructions and SHA-256 values are on the [main download page](https://github.com/HackerChi-Hub/HyphenScreen-Releases). Check for updates through the application menu or download the current package. The Mac 1.4.4 installation matches all 427 files and links, with a valid local signature. The installed API has processed and exported a face-restored clip, retained identical decoded audio, and restored the original. The development desktop passed processing, apply, playback and restore actions; the installed desktop loaded the panel, but its repeat click check was interrupted by the Mac locking. Windows/Linux still need desktop and face-restoration hardware validation. Region selection is available on macOS/Windows. Animation/settings/export images were captured from a 1.1.0 demo project on macOS; screenshots use the Chinese interface. Private review footage is not published here.

Copyright © 2026 HyphenTech. Required third-party licenses and original notices are included in the application. This public repository distributes packages and documentation; source remains private.
