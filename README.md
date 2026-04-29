# AirWave

A lightweight online radio player for macOS.

This repository hosts release artifacts only — installers, archives, checksums,
and the Sparkle auto-update appcast. Each release ships:

- `Airwave-<version>-macos-arm64.pkg` — installer for Apple Silicon
- `Airwave-<version>-macos-x86_64.pkg` — installer for Intel
- `Airwave-<version>-macos-arm64.zip` — drag-and-drop bundle for Apple Silicon
- `Airwave-<version>-macos-x86_64.zip` — drag-and-drop bundle for Intel
- `SHA256SUMS` — SHA-256 hashes for verifying downloads
- `appcast.xml` — Sparkle auto-update feed

## Install

Download the latest `.pkg` for your architecture from the [Releases](https://github.com/b4ryon/AirWave.app/releases/latest) page and run it.

To verify a download:

```bash
shasum -a 256 -c SHA256SUMS
```

## Updates

AirWave 4.1 and later check for updates on every launch and apply them
automatically on the next quit. Manual check via **AirWave > Check for Updates...**.
