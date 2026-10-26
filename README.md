# Workforce downloads

Windows **0.2.6** contains the latest current Agent OS development snapshot (26 October 2026). Existing Windows installations discover it through the normal in-app update feed. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.6)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

The existing local desktop snapshot was packaged without product or test changes. Application builds and source checks, 25/25 focused runtime E2E checks, 3/3 Electron window checks, a synthetic 0.2.5 upgrade and the exact packaged executable passed. Known project-test failures remain, including the incomplete broad unit run and CSS-overlay protection class coverage on the new Remote/Secret forms. This is a development snapshot; consult the release notes and release.json for the complete checks and limits.

Updates and ordinary reinstallations preserve app data. To start fresh, fully quit the app from its tray menu and back up/rename `%APPDATA%\Proactive Agent Workforce`; the next launch creates a new profile. The separate `%USERPROFILE%\Workforce` workspace and existing CLI logins are independent. Keep backups when moving between versions; an older executable alone is not a data restore.

Installers are unsigned; macOS uses manual installation.
