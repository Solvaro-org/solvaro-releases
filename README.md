# Solvaro Desktop — Releases

Official download location for the Solvaro desktop app (formerly **Arcus**).

## Download (current Latest: v1.5.2)

| Platform | Version | Download |
|---|---|---|
| Windows x64 | 1.5.2 | [Solvaro-Setup-1.5.2.exe](https://github.com/Solvaro-org/solvaro-releases/releases/download/v1.5.2/Solvaro-Setup-1.5.2.exe) |
| macOS Apple silicon | 1.4.2 — legacy Arcus build (pre-rebrand; Solvaro Mac build coming) | [Arcus-1.4.2-arm64.dmg](https://github.com/Solvaro-org/solvaro-releases/releases/download/v1.4.2/Arcus-1.4.2-arm64.dmg) |
| macOS Intel | 1.4.2 — legacy Arcus build (pre-rebrand; Solvaro Mac build coming) | [Arcus-1.4.2.dmg](https://github.com/Solvaro-org/solvaro-releases/releases/download/v1.4.2/Arcus-1.4.2.dmg) |
| Linux | 1.4.1 — legacy Arcus build (pre-rebrand; Solvaro Linux build coming) | [AppImage](https://github.com/Solvaro-org/solvaro-releases/releases/download/v1.4.1/Arcus-1.4.1.AppImage) · [.deb](https://github.com/Solvaro-org/solvaro-releases/releases/download/v1.4.1/arcus-desktop_1.4.1_amd64.deb) |

All releases: [Solvaro-org/solvaro-releases releases](https://github.com/Solvaro-org/solvaro-releases/releases)
Only the Windows build is on 1.5.x today; macOS and Linux 1.5.x builds have not been published yet.

## Install

### Windows
The installer is currently **unsigned**, so Microsoft Defender SmartScreen may warn on first run.
1. Download only from the link above (this repository). Do not run copies from other sources.
2. If your browser flags the download, choose **Keep** (Edge: `...` → Keep → Show more → Keep anyway).
3. When SmartScreen shows "Windows protected your PC", click **More info** → **Run anyway**.

Proceed only if you trust the source. Do not disable SmartScreen, Defender, or other security features.

### macOS (1.4.2, unsigned, not notarized)
Gatekeeper blocks a normal double-click. Right-click (Control-click) the app → **Open** → **Open**. Pick the arm64 DMG for Apple silicon, the other for Intel.

## Auto-update
The release notes for 1.5.0–1.5.2 say Windows installs check this repository's latest published release (`latest.yml`) and update to it. They also say 1.5.x keeps the Arcus app ID, so Arcus 1.4.x installs upgrade in place with their connectors and session kept. We have not tested this independently. Draft releases are not published, so they are not offered as updates.
