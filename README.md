# Proactive Agent Workforce — desktop downloads

[Windows x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe) · [Linux x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage) · [macOS Intel + Apple Silicon](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)

These links stay the same and always lead to the latest regular release. [Version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json) · [All versions and release notes](https://github.com/teydra/proactive-agent-workforce-releases/releases)

## What is available now

Optional company/person details and connections in a restrained Codex-inspired desktop shell. Sign in through installed official Codex or Claude Code clients, or use OpenAI/Anthropic API keys and local-server connections. Connection keys use OS-protected storage. All connections can be skipped. The bottom-left profile icon opens the name/settings menu. The name and gear open the same Settings dialog, with separate Profile and Connections sections. Agent execution is not included in this stage.

The app detects updates in the background on launch and while running. A small blue action appears at the lower left when an update is available, with a ring and short progress tooltip during download. On Windows/Linux, clicking it downloads and applies the update with a restart. Linux updating requires running the AppImage. macOS currently uses a downloaded installer until Apple signing is configured.

## Install

- **Windows:** run the installer. It installs for your user and offers a desktop shortcut.
- **Linux:** make the AppImage executable and run it. If FUSE is unavailable, its `--appimage-extract-and-run` option is supported.
- **macOS:** open the universal DMG and copy the application into Applications.

Initial installers are not publisher-signed/notarized. Normal OS trust checks may therefore require review; production signing is still open work. Use this repository's release files and included checksums. Further architectures and distributions are not yet verified.

This repository hosts public binaries and release information. Private project conversations, credentials and research are not published here.
