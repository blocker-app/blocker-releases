# Blocker: Public Release Artifacts

This repository hosts the publicly downloadable `.dmg` build of [Blocker](https://getblocker.app), a minimal macOS website blocker. The application source code lives in a private repository; only the signed and notarized release binaries are published here.

Website: https://getblocker.app

## Install

```bash
brew install --cask leo-mathurin/blocker/blocker
```

## Manual download

See the [Releases](https://github.com/leo-mathurin/blocker-releases/releases) page. Each release ships a single universal `.dmg` that runs natively on both Apple Silicon (M1/M2/M3/M4) and Intel Macs:

- `blocker-<version>.dmg`

All builds are signed with a Developer ID certificate and notarized by Apple.
