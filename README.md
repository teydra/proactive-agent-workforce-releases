# Workforce downloads

Windows **0.2.0** is an unfinished snapshot of the Agent OS rebuild (19 October 2026), available through the existing in-app update action. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.0)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

The Windows snapshot contains the developing agent/team, chat/task, For you and workspace interfaces with the shared runtime. Functionality is incomplete. TypeScript checks and import boundaries pass; 1,012 of 1,018 unit tests and 20 end-to-end tests pass. Six contract checks fail, one PWA screenshot times out, and one real-provider test is skipped. The source window and demo chat pass; the complete final-package window/chat check was not verified. See the release notes for the exact limits.

Existing Windows installations discover this snapshot on the normal update feed. Click the update action to download and restart. Installers are unsigned; macOS uses a manual installer update. Older versions may not understand a newer database; the importer preserves legacy settings as settings.v7-backup.json. Downloading an older executable alone is not a guaranteed data restore.
