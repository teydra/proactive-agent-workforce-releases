# Proactive Agent Workforce — desktop downloads

[Windows x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe) · [Linux x64](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage) · [macOS Intel + Apple Silicon](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)

These links stay the same and always lead to the latest regular release. [Version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json) · [All versions and release notes](https://github.com/teydra/proactive-agent-workforce-releases/releases)

## What is available now

Desktop 0.1.7 adds multiple chats per agent, searchable single/multiple agent selection and editable chat membership. Chat details open from the top header; the avatar opens agent details and model preferences. A compact growing composer includes text/code file insertion, optional configured speech transcription and optional reading of new replies. Copy icons sit below messages. Group replies are selected manually; full live voice and cross-chat memory remain open.

Optional company/person details and connections in a restrained Codex-inspired desktop shell. Sign in through installed official Codex or Claude Code clients, or use OpenAI/Anthropic API keys and local-server connections. Connection keys use OS-protected storage. All connections can be skipped. The clear profile bubble at the bottom left opens Profile, Usage and Settings. Settings is a full view with General, Profile, Appearance, Connections and Usage. Theme, reduced motion, sidebar visibility and automatic update downloading are functional preferences. Usage displays shared Codex account limits through its installed official client, when available; missing limits are not shown as zero. Text conversations now use explicitly selected API/local models, with saved drafts, history, stop and retry. Autonomous tasks/tools and native subscription inference are not included.

The app detects updates in the background on launch and while running. A small blue action appears at the lower left when an update is available, with the actual percentage inside the centered progress ring during download and a short action tooltip. On Windows/Linux, clicking it downloads and applies the update with a restart. Linux updating requires running the AppImage. macOS currently uses a downloaded installer until Apple signing is configured.

## Install

- **Windows:** run the installer. It installs for your user and offers a desktop shortcut.
- **Linux:** make the AppImage executable and run it. If FUSE is unavailable, its `--appimage-extract-and-run` option is supported.
- **macOS:** open the universal DMG and copy the application into Applications.

Initial installers are not publisher-signed/notarized. Normal OS trust checks may therefore require review; production signing is still open work. Use this repository's release files and included checksums. Further architectures and distributions are not yet verified.

This repository hosts public binaries and release information. Private project conversations, credentials and research are not published here.
