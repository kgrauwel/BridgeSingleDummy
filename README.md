# BridgeSingleDummy

Bridge Single Dummy Analyzer lets you import deals and tournament results from BBO, PBN, Messer and Dibris, then analyze the auction and explore the play with comprehensive single-dummy analysis.

## Downloads and installation

See the [latest release and release notes](https://github.com/kgrauwel/BridgeSingleDummy/releases/latest) for installation requirements and known limitations.

Current Windows and Linux version: **v0.9.16-test**. Mac remains the unchanged **v0.9.15-test universal build** for Apple Silicon and Intel. All four downloads are attached to the current release; the Mac filename and included guides retain their actual v0.9.15 version.

| Your platform | Installation file |
| --- | --- |
| Windows 64-bit | [Windows ZIP — v0.9.16](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.16-test/BridgeSingleDummy-v0.9.16-test-win-x64.zip) |
| macOS 14 or newer, Apple Silicon and Intel | [macOS universal ZIP — v0.9.15](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.16-test/BridgeSingleDummy-v0.9.15-test-macos-universal.zip) |
| Ubuntu 22.04+, or compatible Debian/Linux Mint with glibc 2.35+ (x64) | [Linux DEB — v0.9.16](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.16-test/BridgeSingleDummy-v0.9.16-test-linux-x64.deb) |
| Other compatible Linux distributions or manual installation (x64) | [Linux TAR.GZ — v0.9.16](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.16-test/BridgeSingleDummy-v0.9.16-test-linux-x64.tar.gz) |

All packages are self-contained: no separate .NET installation is required. Extract the Windows ZIP completely and start `BridgeSingleDummy.exe`. For Linux, install the DEB with your package manager, or extract the TAR.GZ and run `./BridgeSingleDummy`. Keep all included files together. Updated Dutch, English and French v0.9.16 user guides are included in Windows and Linux; Mac retains its v0.9.15 guides.

These test builds are usable through **31 December 2026** and expire on **1 January 2027**. Keep an older installation separately if you need a fallback; do not overwrite personal data.

The Mac app is ad-hoc signed and **not notarized by Apple**. Follow its package README for first-launch instructions if macOS displays a security warning.

## New in v0.9.16 for Windows and Linux

Line analysis adds adaptive/flexible card instructions, per-step and whole-line explanations, per-line IMP/MP values and individual-deal comparison with CSV/PBN export. Suit combinations compare followable plans with entry constraints and pinned alternatives. Bidding choices support explicit double meanings and partner-response agreements. BBO review includes Traveller and example auctions, and correctly handles passed-out boards.

SD chance full uses an experimental defensive-choice model. SD Robust is bounded to retained DD-optimal defensive branches, not every legal defence. MP/IMP line comparisons are relative to entered alternatives and disclose any restricted common deal basis; they are not tournament-field percentages or a proof of the globally best line. See Help and the release notes for assumptions and limitations.

The four files above are application packages. GitHub's automatically generated "Source code" ZIP/TAR links are not application installers.

Contact: [bridgesingledummy@gmail.com](mailto:bridgesingledummy@gmail.com).
