# Autark desktop downloads

**0.2.8** is available for Windows x64, Linux x64 AppImage and macOS universal (Apple silicon and Intel). It is an isolated snapshot of the ongoing agent/runtime/interface rebuild, captured on 30 October 2026.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.8)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

These are permanent direct-download links: their addresses do not change when a new version is published. Linux downloads the x64 `.AppImage`; macOS downloads the universal `.dmg` for Apple silicon and Intel. They serve the newest published package available for each platform. A Windows-only release retains the latest Linux/macOS files together with their platform update manifests; the release tag alone does not indicate their version. See [Linux version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-linux.yml) and [macOS version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-mac.yml).

Native packaged startup, SQLite, speech addon, a demo runtime chat and the first desktop window passed on Windows, Linux, Apple silicon and Intel. The same 226 compiled application files were checked against the isolated snapshot on each host. The broad unit inventory still contains 15 open assertions; see [verification metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json). Production type checks, the app build, 14 runtime/upgrade checks and 9 NSIS compiler/integrity checks passed. Real accounts, devices and all platform features are not fully accepted.

Windows remains unsigned; SmartScreen may warn and Smart App Control may block it. macOS is ad-hoc signed, without Developer ID or notarization, and may be blocked by Gatekeeper. Linux needs FUSE 2, a working Chromium sandbox and a running secure system keyring. Its native desktop checks used a configured Ubuntu VM; normal user-device AppImage/FUSE acceptance remains open. No security policy was disabled.

Source code and the active development checkout remain private and separate. The manual [compiled-snapshot workflow](.github/workflows/release-from-compiled.yml) builds an explicitly provided, integrity-checked payload into an unpublished draft. It does not watch or copy the development checkout and does not publish a release automatically. Before publishing a single-platform update, retain the last packages and matching manifests of the other platforms so every permanent link keeps working.
