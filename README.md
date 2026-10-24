# Workforce downloads

Windows **0.2.5** contains the latest current Agent OS development snapshot (24 October 2026). Existing Windows installations discover it through the normal in-app update feed. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.5)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

My day, calendar planning, Work input splitting, revised Home/Team pages, chat adjustments and the quota refresh correction are included. The packaged executable was checked in a fresh isolated profile, including demo chat and My day, light/dark, 640x480 and a 390-pixel viewport. Initial full unit suite: 4965/4967 passed (2 skipped); after the quota correction, affected unit areas passed 233/233. Final snapshot: initial focused E2E 46/47 (one screenshot timeout; unchanged affected-file rerun 2/2), initial Electron window checks 8/10 (two test-only corrections; affected-file rerun 2/2). Electron 44.9.3 and dependency patches are included; the final npm audit reports zero vulnerabilities. This remains a development snapshot: real Google Calendar, physical devices, overnight use and an intermittent recorder issue remain subject to acceptance work. Detailed verification and limits are in the release notes and release.json.

Updates and ordinary reinstallations preserve app data. To start fresh, fully quit the app from its tray menu and back up/rename `%APPDATA%\Proactive Agent Workforce`; the next launch creates a new profile. The separate `%USERPROFILE%\Workforce` workspace and existing CLI logins are independent. Keep backups when moving between versions; an older executable alone is not a data restore.

Installers are unsigned; macOS uses manual installation.
