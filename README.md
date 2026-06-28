# PixelFixer 🎮

A free, open source browser tool built for game devs and pixel artists who work with sprites. No installs, no sign-ups, no backend — everything runs locally in your browser.

---

## What it does

### 🎨 Pixelizer
Turn any image into pixel art in one click. Upload a PNG, JPG or WebP, pick your pixel block size, color count, and optionally load a custom `.hex` palette from Lospec or Aseprite. Supports ordered (Bayer) dithering and green screen removal for sprites with a background color.

### ✂️ Smart Cut
Upload a sprite sheet and let PixelFixer detect, cut and normalize every frame automatically — even multi-row sheets. Removes the background via chroma key, trims each sprite to its bounding box, and normalizes all frames to the same canvas size. Preview your animation live with onion skin support, reorder frames however you want, flip the preview horizontally, and export as a sprite sheet PNG or a ZIP of individual frames at 1x, 2x or 4x scale.

---

## Features

- **Auto background detection** — samples corners to detect the chroma key color
- **Smart Cut multi-row** — flood fill algorithm finds sprites across any sheet layout
- **Frame reordering** — click to select frames in any order; the badge shows your custom sequence
- **Onion skin** — see the previous frame ghosted behind the current one while previewing
- **Flip preview** — mirror your animation horizontally without touching the export
- **Export scale** — export at 1x, 2x or 4x without affecting the preview
- **Custom `.hex` palettes** — drag and drop a Lospec palette file directly onto the palette area
- **No dependencies** — single HTML file, works offline, no server required

---

## Usage

Just open `index.html` in any modern browser. That's it.

Or use the live version at: **[https://renevalenz.github.io/pixelfixer/**

---

## Open Source

PixelFixer is free and open source. Use it, fork it, build on it.

If you make something cool with it, share it.

---

## Tech

Vanilla HTML + CSS + JavaScript. Zero frameworks. Zero build steps. One file.

---

Made with ☕ for the pixel art community.
