# Workforce downloads

Windows **0.2.4** contains the latest current Agent OS development snapshot (24 October 2026). Existing Windows installations discover it through the normal in-app update feed. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.4)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

The embedded TeleCoding view is included. The exact packaged Windows executable was started with a fresh isolated profile and a demo chat; light/dark, 640x480 and a 390-pixel viewport were checked. All seven build targets, four TypeScript layers and import boundaries passed. Focused E2E checks passed 41/41 and Electron window checks 5/5. The full initial unit run found nine Windows line-ending assumptions in tests; those test files were corrected and passed 58/58 on rerun. Detailed counts and limits are in the release notes and release.json. This remains a development snapshot with open concept features and hardware/provider acceptance limits.

Updates and ordinary reinstallations preserve app data. To start fresh, fully quit the app from its tray menu and back up/rename `%APPDATA%\Proactive Agent Workforce`; the next launch creates a new profile. The separate `%USERPROFILE%\Workforce` workspace and existing CLI logins are independent. Keep backups when moving between versions; an older executable alone is not a data restore.

Installers are unsigned; macOS uses manual installation.
