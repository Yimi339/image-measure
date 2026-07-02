# Image Measure · 图像测量

A lightweight single-file web tool for measuring **distances**, **angles**, and **areas** directly in images. Works in any modern browser — no install, no dependencies, no build step.

![macOS-friendly](https://img.shields.io/badge/macOS-ready-blue) ![single-file](https://img.shields.io/badge/single-HTML--file-orange) ![zero-deps](https://img.shields.io/badge/dependencies-zero-green)

## Features

- **Distance** — click 2 points
- **Angle** — click 3 points (P1 → vertex → P2)
- **Area** — click N points to form a polygon, click near the start point to close
- **Calibration** — set a known real-world reference (e.g. credit card 8.56 cm wide) to convert pixels to mm / cm / inch
- **Zoom & Pan** — scroll wheel zooms around cursor; hold <kbd>Space</kbd> + drag to pan
- **Drag & Drop** — drop an image onto the window, or paste a screenshot with <kbd>⌘V</kbd>
- **Light / Dark mode** — auto-detects system preference; toggle with the 🌙 / ☀️ button (preference is remembered)
- **Measurements list** — click any item to flash its overlay; <kbd>×</kbd> to delete

## Quick Start

1. Download [`index.html`](./index.html) (or clone this repo)
2. Double-click to open in any modern browser (Safari, Chrome, Firefox, Edge)
3. Drop / paste / open an image and start measuring

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Zoom | Mouse wheel |
| Pan | Hold <kbd>Space</kbd> + drag |
| Cancel current measurement | <kbd>Esc</kbd> |
| Paste image from clipboard | <kbd>⌘V</kbd> / <kbd>Ctrl+V</kbd> |
| Reset zoom to fit | Click **⊡ 适配** |

## Why

PowerPoint and Keynote lack an "arbitrary point-to-point measurement" tool — they only show rulers, guides, and selected-object dimensions. This tool fills that gap for anyone who needs to measure things on a screenshot, photo, or sketch.

## Tech

Pure vanilla HTML + CSS + JS. No frameworks, no build step, no network requests at runtime. All logic and styles are inlined in a single ~860-line file.

## License

MIT — see [LICENSE](./LICENSE).