# Autark desktop downloads

**0.2.9** is available for Windows x64, Linux x64 AppImage and macOS universal (Apple silicon and Intel), captured from the current development state on 1 November 2026.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe)
- [Linux x64 AppImage](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage)
- [macOS universal DMG](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.2.9)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

These permanent direct-download links keep their addresses when a new version is published. Windows and Linux use the existing in-app update channels. Mac updates remain a manual download until Developer ID signing and notarization are available. Platform versions are recorded in [Windows metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest.yml), [Linux metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-linux.yml) and [Mac metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-mac.yml). Future single-platform releases retain the other platforms' packages and matching manifests.

Native packaged startup, SQLite, speech addon, a demo runtime chat and the first desktop window passed on Windows, Linux, Apple silicon and Intel. All 218 compiled application files matched on every host. Type checks, import boundaries and six build targets passed. The full unit run recorded 4,268 passes, one Linux timing failure under Windows and two skips; that timing test passed natively under Linux. Runtime checks initially passed 23 of 24 assertions; the outdated memory-ID assertion was corrected to verify full contents and the old-ID alias across restarts, and both upgrade checks passed. Exact results are in [verification metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json).

Windows remains unsigned. macOS is ad-hoc signed, without Developer ID or notarization. Operating-system trust policies still apply. Linux needs FUSE 2, a working Chromium sandbox and a secure system keyring; its native desktop checks used a configured Ubuntu CI host. A full native installation/update cycle, normal user-device AppImage/FUSE acceptance and real provider/device features were not established by these checks.

Product sources remain private. The manual [compiled-snapshot workflow](.github/workflows/release-from-compiled.yml) builds an explicitly supplied, integrity-checked payload into an unpublished draft. The [Intel verification workflow](.github/workflows/verify-mac-intel.yml) checks that same universal Mac ZIP. Neither workflow publishes a release automatically.
