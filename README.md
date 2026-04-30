# Blocker: Public Release Artifacts

This repository hosts the publicly downloadable `.dmg` builds of [Blocker](https://getblocker.app), a minimal macOS website blocker. The application source code lives in a private repository; only the signed and notarized release binaries are published here.

Website: https://getblocker.app

## Install

```bash
brew install --cask leo-mathurin/blocker/blocker
```

## Manual download

See the [Releases](https://github.com/leo-mathurin/blocker-releases/releases) page. Each release ships two architectures:

- `blocker-<version>-arm64.dmg`: Apple Silicon (M1/M2/M3/M4)
- `blocker-<version>-x64.dmg`: Intel

All builds are signed with a Developer ID certificate and notarized by Apple.
