# BridgeSingleDummy

Bridge Single Dummy Analyzer lets you import deals and tournament results from
BBO, PBN, Messer and Dibris, analyze the auction and explore the play with
single-dummy analysis.

## Downloads and installation

See the [latest release and release notes](https://github.com/kgrauwel/BridgeSingleDummy/releases/latest)
for installation requirements and known limitations.

Current version for Windows, Linux and macOS: **v0.9.15-test**, including a new universal Mac build for Apple Silicon and Intel.

| Your platform | Installation file |
| --- | --- |
| Windows 64-bit | [Windows ZIP — v0.9.15](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.15-test/BridgeSingleDummy-v0.9.15-test-win-x64.zip) |
| macOS 14 or newer, Apple Silicon and Intel | [macOS universal ZIP — v0.9.15](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.15-test/BridgeSingleDummy-v0.9.15-test-macos-universal.zip) |
| Ubuntu 22.04+, or compatible Debian/Linux Mint with glibc 2.35+ (x64) | [Linux DEB — v0.9.15](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.15-test/BridgeSingleDummy-v0.9.15-test-linux-x64.deb) |
| Other compatible Linux distributions or manual installation (x64) | [Linux TAR.GZ — v0.9.15](https://github.com/kgrauwel/BridgeSingleDummy/releases/download/v0.9.15-test/BridgeSingleDummy-v0.9.15-test-linux-x64.tar.gz) |

All packages are self-contained: no separate .NET installation is required.
Extract the Windows ZIP completely and start `BridgeSingleDummy.exe`. For Linux,
install the DEB with your package manager, or extract the TAR.GZ and run
`./BridgeSingleDummy`. Follow the package README for complete first-launch instructions.
Keep the included program files together. Updated Dutch, English and French user guides are included in every package.

These test builds are usable through **31 December 2026** and expire on
**1 January 2027**. Keep an older installation separately if you need a fallback;
do not overwrite personal data.

The macOS app is ad-hoc signed and **not notarized by Apple**. See its package
README for first-launch instructions if macOS displays a security warning.

## New in v0.9.15

Line analysis has its own settings, a card-click plan editor with editable text notation, more detailed progress and MP/IMP comparison indications. Contract analysis uses stronger automatic sampling checks, and the experimental SD chance model has improved tactical follow-suit choices. The original-hands window now includes the auction and vulnerability.

SD chance full uses an experimental defensive-choice model; its percentages are
estimates under that model. SD Robust is a bounded search, not a guarantee against
every legal defence. See the help and release notes for model assumptions.

The four files above are installers. GitHub's automatically generated "Source code"
ZIP/TAR links are not application installers.

Contact: [bridgesingledummy@gmail.com](mailto:bridgesingledummy@gmail.com).
