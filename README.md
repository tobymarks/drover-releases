# Drover Releases

Signed and notarized builds of [Drover](https://github.com/tobymarks/Drover), a native macOS client for [herdr](https://herdr.dev).

- **Download:** the latest DMG is on the [Releases](https://github.com/tobymarks/drover-releases/releases/latest) page.
- **Updates:** Drover checks `appcast.xml` in this repository with [Sparkle](https://sparkle-project.org) and installs new versions after asking. Every update is signed with Drover's EdDSA key, and Drover refuses anything that isn't.

This repository holds release artifacts only. It is updated by `scripts/publish.sh` in the Drover repository.
