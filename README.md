# Proactive Agent Workforce — desktop downloads

[Windows x64 — 0.1.8](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe) · [Linux x64 — 0.1.7](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage) · [macOS Intel + Apple Silicon — 0.1.7](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)

The stable links remain unchanged. This release updates Windows; Linux/macOS retain the byte-identical previously verified 0.1.7 packages and update manifests. Native CI runners could not start, so no new Linux/macOS build is claimed. [Version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json) · [All versions and notes](https://github.com/teydra/proactive-agent-workforce-releases/releases)

## Windows 0.1.8

One readable Agents list contains independently named conversations. Plus attaches files or folders as removable files, with text/image/readable-PDF previews. Chat details open from the top name; avatars open agent details. Installed signed-in Codex models supply real conversational replies through the official client. API/local model connections remain available. Setup includes a product guide, editable prompt and actual configuration facts.

With an empty composer, the primary button starts/ends a listening conversation; content uses that same position for Send. Windows can use installed local speech recognition, or a configured transcription service. The selected text model responds through the system voice, then listening resumes. This is one half-duplex session, bound to its original chat during navigation. Dictation remains a separate editable-draft action using configured transcription. Native Codex realtime audio requires separate API authentication. Group replies are manually selected; autonomous tasks/tools, shared cross-chat memory and parallel voice sessions remain open.

Profile Usage preserves actual remaining quotas and reset times. The Claude install action uses the official installer. TeleCoding detects its existing local host and shows its actual status/QR. Logins remain in the official clients; API keys use OS-protected storage. All connections and company/person setup are optional.

Windows verification: 72 functional tests, four packaged-window suites, runtime/source byte verification and a real Codex reply from the packaged app. Linux/macOS 0.1.7 retain their earlier native build/window checks.

## Install and update

- **Windows:** run the installer for your user; a desktop shortcut is available. The small blue update action above the profile downloads and applies an available update.
- **Linux:** make the AppImage executable and run it; `--appimage-extract-and-run` is available without FUSE. No new Linux version is offered by this release.
- **macOS:** open the universal DMG and copy the app to Applications. Updates use a downloaded installer until Apple signing is configured.

Installers are not publisher-signed/notarized. Use this repository's release files and included checksums. Private project conversations, credentials and research are not published here.
