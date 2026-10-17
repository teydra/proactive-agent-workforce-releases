# Proactive Agent Workforce — desktop downloads

[Windows x64 — 0.1.9](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-windows-x64.exe) · [Linux x64 — 0.1.7](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-linux-x64.AppImage) · [macOS Intel + Apple Silicon — 0.1.7](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/workforce-mac-universal.dmg)

This release updates Windows. Linux/macOS retain their byte-identical, previously verified 0.1.7 packages and update manifests because GitHub's account limit prevented native runners from starting. [Version metadata](https://github.com/teydra/proactive-agent-workforce-releases/releases/latest/download/release.json) · [All versions and release notes](https://github.com/teydra/proactive-agent-workforce-releases/releases)

## Windows 0.1.9

Conversation names stay separate from messages in the list and header, with a small latest-message preview. Your messages show a small timestamp below their content, without a name heading. The persistent sidebar can be resized, and the chat header stays within the content area. Available weekly quotas and reset dates appear above the profile; provider details open on hover, focus or click. Missing provider values are not invented.

Updates are checked every minute, on focus and after waking. A finished download shows a white checkmark and an explicit Restart action. Optional automatic updates can restart during inactivity after a visible countdown; Later postpones the restart. Drafts, pending writes, recordings and ongoing replies prevent an idle restart. Visible drafts are saved before installation, and a failed save leaves the app open for retry.

The installed, signed-in official Codex client supplies model choices and conversational replies; API/local text models remain available. Files and folders attach as persistent removable files with text, image and readable-PDF previews. Setup includes an editable prompt, a product guide and actual configuration facts. TeleCoding recognizes its existing host and pairing state. Connections and person/company setup remain optional.

The empty composer's primary action starts/ends one listening conversation. Windows can use installed local speech recognition or configured transcription. The selected text model responds through system speech, then listening resumes. Dictation remains a separate editable-draft action. Native Codex realtime voice requires separate API authentication. Group replies are selected manually; autonomous tools/tasks, shared cross-chat memory and simultaneous independent voice sessions remain open.

Verification: 82 functional tests and seven source-window suites passed. All 29 runtime files match the previously opened and tested local package and the private source commit. Windows application control blocked launching the final 0.1.9 executable (CodeIntegrity 3077); no successful final-binary start or installation is claimed, and no policy was bypassed. Linux/macOS 0.1.7 retain their earlier native build/window checks.

## Install and update

- **Windows:** run the installer for your user. The small blue update action above the profile downloads and applies an available update. The improved update UI becomes available after installing 0.1.9.
- **Linux:** make the AppImage executable and run it; `--appimage-extract-and-run` is available without FUSE. This release offers no new Linux version.
- **macOS:** open the universal DMG and copy the app to Applications. Updates use downloaded installers until Apple signing is configured.

Replacing Windows program files can temporarily leave the desktop shortcut target unavailable. Installer speed and relaunch under every application-control policy have not been verified. Installers are not publisher-signed/notarized and may be blocked by local policy. Use this repository's release files and checksums. Private project conversations, credentials and research are not published here.
