# Workforce downloads

Windows **0.2.1** is an unfinished snapshot of the current Agent OS rebuild (21 October 2026). Existing Windows installations discover it through the normal in-app update feed. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG (0.1.7)](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.1)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

This snapshot captures ongoing development so the current desktop app can be inspected. It is not a completed Agent OS. The full TeleCoding embedded view exceeds the transport size limit and is unavailable in this desktop snapshot. See the release notes and release.json for the actual test results and remaining limits.

Installers are unsigned; macOS uses manual installation. Older apps may not understand a newer database. Keep backups when moving between versions; downloading an older executable alone is not a data restore.
