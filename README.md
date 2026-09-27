# Ngeshare Desktop — Releases

Public distribution point for **Ngeshare Desktop**, the Tauri-wrapped desktop build of the Ngeshare learning platform.

> Source code lives in the private repo `ngeflow/faster-desktop`. This repo only hosts the download page and release binaries.

## Download

Landing page: https://ngeflow.github.io/faster-desktop-releases/

Evergreen direct links (always point at the latest release):

- macOS (Apple Silicon): https://github.com/ngeflow/faster-desktop-releases/releases/latest/download/Ngeshare-Desktop-0.16.5-aarch64.dmg
- Windows (x64): https://github.com/ngeflow/faster-desktop-releases/releases/latest/download/Ngeshare-Desktop-0.16.5-x64-setup.exe

## Docs

- [Hangout Online — Web-Based Version with a Local Server](https://ngeflow.github.io/faster-desktop-releases/hangout-online-web-based-explainer.html): why we test Hangout Online in the browser first, and how that gives confidence in the desktop app.

## Install

### macOS (Apple Silicon)

1. Download the `.dmg`, open it, drag **Ngeshare Desktop** to Applications.
2. The app isn't signed/notarized yet, so Gatekeeper will block the first launch. Either:   - Right-click the app → **Open** → confirm, or
   - Strip the quarantine flag: `xattr -cr "/Applications/Ngeshare Desktop.app"`

### Windows (x64)

1. Download the `.exe`, run it.
2. Windows SmartScreen may show an "unrecognized app" prompt — click **More info** → **Run anyway** (the app is currently unsigned).

## System requirements

- **macOS**: 11 Big Sur or later, Apple Silicon (M1/M2/M3/M4).
- **Windows**: 10 or later, 64-bit.

## Releases

See [all releases](https://github.com/ngeflow/faster-desktop-releases/releases) for older versions and changelogs.
