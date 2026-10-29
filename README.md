# DeTwin Memory Check

Installer downloads for DeTwin Memory Check. This repository contains download
instructions and packaged applications, not the private application sources or
any conversation data. Downloads require no GitHub account once published.

## Version 0.12.142

| Computer | Installer |
| --- | --- |
| Windows x64 | [Download EXE](https://github.com/eternalTech-ai/detwin-memory-check-downloads/releases/download/v0.12.142/DeTwin-Memory-Check-0.12.142-Windows-x64.exe) |
| Mac with Apple M-series chip | [Download PKG](https://github.com/eternalTech-ai/detwin-memory-check-downloads/releases/download/v0.12.142/DeTwin-Memory-Check-0.12.142-Mac-Apple-Silicon.pkg) |
| Mac with Intel processor | [Download PKG](https://github.com/eternalTech-ai/detwin-memory-check-downloads/releases/download/v0.12.142/DeTwin-Memory-Check-0.12.142-Mac-Intel.pkg) |

Choose Apple menu > About This Mac to check your Mac's chip. A DMG is also
available in the [release files](https://github.com/eternalTech-ai/detwin-memory-check-downloads/releases/tag/v0.12.142).

## Install and enable local analysis

Before upgrading, choose **Quit** in the existing app's system tray/menu bar. Closing its window can leave background monitoring running.

1. Open the EXE on Windows, or open the PKG on Mac and follow Installer.
   On Mac, start DeTwin Memory Check from Applications afterward.
2. Authorize the detected local histories you want inspected.
3. Open **AI settings > Download local AI > Download & enable**. Select
   **All dated history** if you want all available dated history included.

The guided AI setup downloads and verifies Qwen3.5 9B, approximately 5.7 GB,
plus platform runtime files. The model is not embedded in the small installer.
Initial internet access is required; interrupted downloads can be retried.
Local analysis does not require an AI API key or a new Claude/Codex login.
Your conversations are processed on your device. Background monitoring is
optional; Quit stops it.

Mac local AI requires **macOS 13.3+, 16 GB RAM and 12 GB free disk**.
Automatic mode requests Metal on Apple Silicon; Intel uses CPU.

## Release status

These are validation builds. Windows is unsigned; the Mac app is ad-hoc signed,
the PKG is unsigned, and neither Mac package is Apple-notarized. Operating-system
security checks may block installation or launch. Do not disable security
protections to open these packages. Signed public-release acceptance is pending.

Package installation/startup checks do not establish successful 9B inference on
every Mac, semantic accuracy, full-year review within an hour, or guaranteed
savings. AI review is progressive; economic figures are estimates, not invoices
or proven losses. Check the release's **SHA256SUMS.txt** to verify downloads.
