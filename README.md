# Workforce downloads

Windows **0.2.7** repairs Restart to Update (27 October 2026): direct executable relaunch after installation, recovery after installer-start failures and safe update diagnostics. Linux and macOS remain at **0.1.7**.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.7)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

These are permanent direct-download links: their addresses do not change when a new version is published. Linux downloads the x64 `.AppImage`; macOS downloads the universal `.dmg` for Apple silicon and Intel. They serve the newest published package available for each platform. A Windows-only release retains the latest Linux/macOS files together with their platform update manifests; the release tag alone does not indicate their version. See [Linux version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-linux.yml) and [macOS version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-mac.yml).

Based on 0.2.6 with only the scoped Windows updater repair. Forty focused updater/lifecycle checks, nine compiler/integrity checks, the application build, type checks, exact packaged app, synthetic profile upgrade and native automatic relaunch passed. Consult release.json and the release notes for package/native verification and remaining limits. Previously documented broad project-test failures remain open.

Updates and ordinary reinstallations preserve app data. If an older installation keeps offering Restart to Update, fully quit it from the tray menu and run the Windows installer above once. Keep a backup when moving between versions; an older executable alone is not a data restore.

Installers are unsigned; macOS uses manual installation.
