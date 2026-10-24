<h1 align="center">Anton Parkhomenka · <code>lemitz</code></h1>

<p align="center">
  <b>AI-Native Systems Builder · AI Operations & Automation · Technical Pre-Sale & Product Producer</b><br>
  Designing, orchestrating, and shipping working local-first software & self-hosted systems entirely through AI-driven development.<br>
  <i>Human architecture & taste. AI-generated code. Real working binaries.</i>
</p>

<p align="center">
  <a href="https://about.kobyla.by"><img src="https://img.shields.io/badge/dossier-about.kobyla.by-8b8cff" alt="about.kobyla.by"></a>
  <a href="https://kobyla.by"><img src="https://img.shields.io/badge/main_world-kobyla.by-e8590c" alt="kobyla.by"></a>
  <a href="https://www.linkedin.com/in/lemitz/"><img src="https://img.shields.io/badge/LinkedIn-in%2Flemitz-0077b5" alt="LinkedIn"></a>
  <a href="https://t.me/LemiTZ"><img src="https://img.shields.io/badge/Telegram-%40LemiTZ-24c8db" alt="Telegram"></a>
  <a href="mailto:hello@kobyla.by"><img src="https://img.shields.io/badge/email-hello%40kobyla.by-2ea043" alt="Email"></a>
</p>

<p align="center">
  <b>English</b> · <a href="README.ru.md">Русский</a>
</p>

---

### How I Build (100% AI-Driven Engineering)

By education I am a linguist (English **C2**, German) — **not a traditional manual coder**. I don't type syntax line by line. Instead, I use LLMs and coding agents as a full-scale production layer ("second brain"):
- **I own the human layer:** problem definition, system architecture, security & threat modeling, UX/UI logic, hardware/network integration, QA, and release packaging.
- **AI handles the syntax layer:** writing implementation code across `Kotlin`, `C# / .NET`, `Rust / Tauri`, `Go`, `Flutter`, and `TypeScript` under my strict specification and verification.
- **The result:** real, zero-telemetry software that compiles, passes tests, and runs on my own devices every single day.

### Shipped AI-Driven Software & Systems

| Project | Stack & Platform | Architecture & Purpose | Status / Release |
| :--- | :--- | :--- | :--- |
| **[Rocket](https://github.com/lemitz/Rocket)** | `Go` · `Direct2D` · `Kotlin` *(Windows 10/11 & Android 14+)* | Zero-dependency Wi-Fi file transfer ("pick files, slide, fly"). Pure stdlib Go on PC + pure platform Kotlin on Android, CRC32C verification, auto-discovery, 120 Hz/vsync rocket UI. | [![v0.2.0](https://img.shields.io/badge/release-v0.2.0-8b8cff)](https://github.com/lemitz/Rocket/releases) |
| **[FeatherW8](https://github.com/lemitz/FeatherW8)** | `Kotlin` · `Jetpack Compose` · `Media3` · `C++/JNI` *(Android 9+)* | Offline local music player with a custom native **DSD (`DSF`/`DSDIFF`) → PCM** decoder, true-black AMOLED UI, 120 Hz support, Nothing/realme integrations. Zero network permissions. | [![v1.4.1](https://img.shields.io/badge/release-v1.4.1-3ddc84)](https://github.com/lemitz/FeatherW8/releases) |
| **[FeatherW8-CLI](https://github.com/lemitz/FeatherW8-CLI)** | `C#` · `.NET 10` · `ASIO` · `WASAPI Exclusive` *(Windows 10/11)* | Terminal bit-perfect audio player (`MP3`, `WAV`, `FLAC`, `Ogg`, `Opus`, native `DSD` over ASIO). Built around hardware DACs (FiiO K11) — zero software resampling or mixer degradation. | [![v1.2.1](https://img.shields.io/badge/release-v1.2.1-0078d4)](https://github.com/lemitz/FeatherW8-CLI/releases) |
| **[MDPad](https://github.com/lemitz/MDPad)** | `Rust` · `Tauri 2` · `TypeScript` · `CodeMirror 6` *(Windows 10/11)* | Instant-start native Markdown notepad. Live CommonMark/GFM split preview, automatic encoding preservation (`UTF-8`, `UTF-16`, `Windows-1251`), physical keycode shortcuts for Cyrillic layouts. | [![v1.0.3](https://img.shields.io/badge/release-v1.0.3-24c8db)](https://github.com/lemitz/MDPad/releases) |
| **[HomeLAN_2026](https://github.com/lemitz/HomeLAN_2026)** | `Go` · `SQLCipher` · `Flutter` · `WebSockets` *(Orange Pi / Linux / Win / Android)* | Self-hosted E2E-encrypted (`X25519` + `ChaCha20-Poly1305`) LAN messenger for a closed network. Features hardware USB Master Key check, Duress Password wipe, and NTP-free time delta sync. | [![v0.5.0-rc](https://img.shields.io/badge/source-v0.5.0_RC-7f52ff)](https://github.com/lemitz/HomeLAN_2026) |
| **[KOBYLA.BY](https://kobyla.by)** | `Nuxt 3` · `TypeScript` · `Cloudflare Pages` *(Web)* | Interactive digital laboratory: **122 content nodes**, causal routing, Windows XP desktop layer, playable Solitaire, and 16 distinct visual modes. Professional entry at **[about.kobyla.by](https://about.kobyla.by)**. | [![live](https://img.shields.io/badge/status-live-2ea043)](https://about.kobyla.by) |
