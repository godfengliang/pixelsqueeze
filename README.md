# PixelSqueeze

[![Live Demo](https://img.shields.io/badge/Live_Demo-pixelsqueeze.surge.sh-brightgreen?style=for-the-badge)](https://pixelsqueeze.surge.sh)

> Compress images to an exact file size. "Make this under 100KB." Done.

**Try it now:** [pixelsqueeze.surge.sh](https://pixelsqueeze.surge.sh)

## Why?

Every job application, government form, and forum has arbitrary file size limits. "Image must be under 100KB." "Max 200KB profile picture." Existing tools don't let you set a **target size** — they just compress blindly.

PixelSqueeze lets you type the exact size you need and binary-searches the best quality/resize combo to hit it.

## Features

- **Exact target size** — "100 KB", "1 MB", any size you need
- **Binary search algorithm** — finds the best quality that fits
- **Batch mode** — compress multiple files at once
- **Smart scaling** — reduces dimensions only if quality alone isn't enough
- **Download individually or all at once**
- **No upload** — everything happens in your browser via Canvas API

## Tech

Single HTML file. Zero dependencies. Pure Canvas API binary search.

## License

MIT
