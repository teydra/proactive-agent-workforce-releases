# Workforce downloads

Windows **0.2.2** contains the audited Agent OS rebuild and integration fixes (21 October 2026). Existing Windows installations discover it through the normal in-app update feed. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.2)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

The embedded TeleCoding view is included and below its transport limit. The packaged Windows executable was launched with a fresh isolated profile and checked with a demo chat. The full source check passed 3,540 unit tests. This remains a development snapshot with open concept features and hardware/provider verification limits; see the release notes and release.json.

Updates and ordinary reinstallations preserve app data. To start fresh, fully quit the app from its tray menu and back up/rename `%APPDATA%\Proactive Agent Workforce`; the next launch creates a new profile. The separate `%USERPROFILE%\Workforce` workspace and existing CLI logins are independent. Keep backups when moving between versions; an older executable alone is not a data restore.

Installers are unsigned; macOS uses manual installation.
