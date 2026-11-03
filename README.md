# Autark desktop downloads

**0.3.0** is available for Windows x64, Linux x64 AppImage and macOS universal (Apple silicon and Intel). With this release the app formerly called Proactive Agent Workforce is named Autark.

- [Windows x64 installer](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/autark-windows-x64.exe)
- [Linux x64 AppImage](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/autark-linux-x64.AppImage)
- [macOS universal DMG](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/autark-mac-universal.dmg)
- [Release notes and verification limits](https://github.com/teydra/proactive-agent-workforce-releases/releases/tag/v0.3.0)
- [Checksums](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/SHA256SUMS.txt)

These permanent direct-download links keep their addresses when a new version is published. Release 0.3.0 also carries the same three packages under their old names (`workforce-windows-x64.exe`, `workforce-mac-universal.dmg`, `workforce-linux-x64.AppImage`), byte for byte, so older links keep working. The update metadata names only the `autark-*` files.

Windows and Linux update in the app. On its first start, 0.3.0 moves the data folder once from the old name to `Autark`. On the Mac, 0.2.9 gets 0.3.0 as a manual download once. From 0.3.0 on, the Mac app can replace itself with a later version; that path has not yet run on a real Mac. Platform versions are recorded in [Windows metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest.yml), [Linux metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-linux.yml) and [Mac metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/latest-mac.yml). Future single-platform releases retain the other platforms' packages and matching manifests.

What was checked for this release, and what was not, is listed in the release notes and in [verification metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json).

Windows remains unsigned. macOS is ad-hoc signed, without Developer ID or notarization. Operating-system trust policies still apply. Linux needs FUSE 2, a working Chromium sandbox and a secure system keyring; its native desktop checks used a configured Ubuntu CI host.

Product sources remain private. The manual [compiled-snapshot workflow](.github/workflows/release-from-compiled.yml) builds an explicitly supplied, integrity-checked payload into an unpublished draft. The [Intel verification workflow](.github/workflows/verify-mac-intel.yml) checks that same universal Mac ZIP. Neither workflow publishes a release automatically.
