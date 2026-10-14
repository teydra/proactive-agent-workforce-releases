# Proactive Agent Workforce — desktop downloads

[Windows x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe) · [Linux x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage) · [macOS Intel + Apple Silicon](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)

These links stay the same and always lead to the latest regular release. [Version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json) · [All versions and release notes](https://github.com/teydra/proactive-agent-workforce-releases/releases)

## What is available now

Desktop setup with optional workspace details, checked OpenAI/Anthropic API and local-server connections, OS-protected API key storage, and GitHub update delivery. Agent execution is not included in this initial stage. API connections need your own provider key; subscription sign-in is separate future work.

The app checks for updates on launch and every 30 minutes while running. On Windows and Linux you can download on click or enable automatic downloads; restart to install when ready. Linux updating requires running the AppImage. macOS currently uses a downloaded installer until Apple signing is configured.

## Install

- **Windows:** run the installer. It installs for your user and offers a desktop shortcut.
- **Linux:** make the AppImage executable and run it. If FUSE is unavailable, its `--appimage-extract-and-run` option is supported.
- **macOS:** open the universal DMG and copy the application into Applications.

Initial installers are not publisher-signed/notarized. Normal OS trust checks may therefore require review; production signing is still open work. Use this repository's release files and included checksums. Further architectures and distributions are not yet verified.

This repository hosts public binaries and release information. Private project conversations, credentials and research are not published here.
