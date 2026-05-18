# Hi, I'm Alexander 👋

**Senior Software Engineer · Haxe expert & open-source maintainer.** ~20 years shipping production code: cross-platform engines and tooling, real-time graphics, computer vision. I like hard native problems and long-lived libraries.

[![Haxe](https://img.shields.io/badge/Haxe-EA8220?style=flat&logo=haxe&logoColor=white)](https://haxe.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![C++](https://img.shields.io/badge/C++17-00599C?style=flat&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![ActionScript](https://img.shields.io/badge/AS3-CC0000?style=flat&logo=adobe&logoColor=white)](https://airsdk.harman.com/)

---

## ✨ Featured open source

### 🦄 [Pony](https://github.com/axgord/Pony) · `haxelib install pony` [![stars](https://img.shields.io/github/stars/axgord/Pony?style=flat&label=%E2%AD%90&color=DE8F00)](https://github.com/axgord/Pony/stargazers)
Open-source cross-library and build toolchain for Haxe — **develop, build, test and publish** apps for Heaps, PixiJS, OpenFL, NodeJS, Electron, Cordova, PHP, Unity3D, Flash and Cocos Creator. XML-based UI system, powerful event system, scaffolding CLI. A long-running personal project, **used in production across multiple commercial games and apps**. MIT.

### 🎬 [extension-video-export](https://github.com/soccertutor/extension-video-export) · `haxelib install extension-video-export`
Cross-platform H.264/MP4 video encoder for OpenFL/hxcpp — encode `BitmapData` frames to MP4 via native APIs, no FFmpeg. Per-platform backends: **AVFoundation + IOSurface/Metal** (macOS/iOS), **Media Foundation + PBO readback** (Windows), **NDK AMediaCodec + EGL** (Android), **OpenH264 + minimp4** (Linux). GPU & CPU paths, B-frame-aware buffer pooling, async dispatch. Built for **[Tactics Manager](https://www.soccertutor.com)** (football-tactics animation software) to export tactic animations as video — open-sourced under MIT.

### 💾 [extension-file-save](https://github.com/soccertutor/extension-file-save) · `haxelib install extension-file-save`
Cross-platform OpenFL/Lime native extension for saving files through **native OS file pickers** — `NSSavePanel` (macOS), `UIDocumentPickerViewController` (iOS), `ACTION_CREATE_DOCUMENT` (Android), Lime `FileDialog` (Windows/Linux). Desktop direct-write & mobile copy-to-destination workflows. Built for **[Tactics Manager](https://www.soccertutor.com)** (football-tactics animation software) to save users' work across platforms — open-sourced under MIT.

### 📜 [anyparse](https://github.com/axgord/anyparse)
Declarative parser & writer driven by Haxe types. Build macros synthesize wrapper modules with cyclic type references — grammar-driven code generation, format- and language-agnostic.

## 🤖 Claude Code plugins

| Project | What & why | ⭐ |
|---|---|---|
| **[claude-workflow](https://github.com/axgord/claude-workflow)** | Drives AI agents through YAML state machines — guards, nested workflow stacks, live web dashboard. | [![stars](https://img.shields.io/github/stars/axgord/claude-workflow?style=flat&label=&color=DE8F00)](https://github.com/axgord/claude-workflow/stargazers) |
| **[claude-notify-sounds](https://github.com/axgord/claude-notify-sounds)** | Cross-platform sound notifications when the agent finishes or needs input. | [![stars](https://img.shields.io/github/stars/axgord/claude-notify-sounds?style=flat&label=&color=DE8F00)](https://github.com/axgord/claude-notify-sounds/stargazers) |
| **[claude-keep-awake](https://github.com/axgord/claude-keep-awake)** | Keeps the machine awake while the agent works. | [![stars](https://img.shields.io/github/stars/axgord/claude-keep-awake?style=flat&label=&color=DE8F00)](https://github.com/axgord/claude-keep-awake/stargazers) |

## 🧰 Tooling & engine integration

| Project | What & why | ⭐ |
|---|---|---|
| **[FD-Haxe-Up](https://github.com/axgord/FD-Haxe-Up)** | FlashDevelop project templates & features for Haxe — predates current Haxe IDE support. | [![stars](https://img.shields.io/github/stars/axgord/FD-Haxe-Up?style=flat&label=&color=DE8F00)](https://github.com/axgord/FD-Haxe-Up/stargazers) |
| **[haxe-cc](https://github.com/axgord/haxe-cc)** | Strongly-typed Haxe externs for the Cocos Creator game engine. | [![stars](https://img.shields.io/github/stars/axgord/haxe-cc?style=flat&label=&color=DE8F00)](https://github.com/axgord/haxe-cc/stargazers) |
| **[hx-monaco-editor](https://github.com/axgord/hx-monaco-editor)** | Haxe externs for the Monaco editor. | [![stars](https://img.shields.io/github/stars/axgord/hx-monaco-editor?style=flat&label=&color=DE8F00)](https://github.com/axgord/hx-monaco-editor/stargazers) |
| **[hx-unity3d](https://github.com/axgord/hx-unity3d)** | Archived experiment: cross-compiling Haxe to Unity-compatible C#. | [![stars](https://img.shields.io/github/stars/axgord/hx-unity3d?style=flat&label=&color=DE8F00)](https://github.com/axgord/hx-unity3d/stargazers) |

## 💼 Selected commercial work

- **Computer vision** — designed a high-performance **C++17 face/body recognition pipeline** for Linux digital-signage players: real-time multi-camera detection & tracking on **YOLOv8 + ONNX Runtime**, **ByteTrack** MOT and **person re-identification**. Mutex-free hot path, Intel IPP/SIMD, CMake + Docker multi-stage builds.
- **Digital signage** — built an **AS3→Haxe converter** and an **Adobe AIR API alternative** for browsers, WebOS and Tizen; stable cross-device media playback.
- **Games** — browser & mobile titles: city-builder, 3D racing, platformer with level editor; AWS build & deploy automation, shader VFX, weak-device optimization.

---

❤️ [Sponsor via PayPal](https://paypal.me/axgorde)
