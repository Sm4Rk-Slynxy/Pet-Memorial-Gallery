# 🐾 Pet Memorial Gallery

A beautiful, private memorial gallery for honoring beloved pets. Photos and videos are displayed in decorative frames scattered across the screen like cherished prints laid out on a table — all locally, with nothing ever uploaded.

---

## ✨ Features

- **Three frame styles** randomly mixed each session:
  - 🖼️ **Polaroid** — cream border with tape detail and a handwritten-style caption
  - 🌸 **Cute** — colorful gradient borders (pink, blue, mint, lilac, peach) with paw print & heart corner decorations
  - 🪵 **Rustic / Wooden** — CSS wood-grain texture with inner bevel rings
- **Eight frames** laid out in a scattered table arrangement with natural tilts
- **Two extra-large center frames** as anchor photos
- **Smooth cycling** — frames softly fade between photos every ~9 seconds
- **Hover to lift** — hovering a frame raises and scales it
- **Floating particles** drifting upward in the background
- **100% private** — all media stays on your device; nothing is sent anywhere

---

## 🚀 How to Use

1. **Download** `pet-memorial.html` to anywhere on your computer
2. **Open** it by double-clicking (Chrome or Edge recommended)
3. Click **"Open a Folder of Memories"**
4. Select the local folder containing your photos and/or videos
5. The gallery fills instantly — use **"Change folder"** in the top bar to switch collections

> No server, no install, no account needed. Just a single HTML file.

---

## 📁 Supported Formats

| Type   | Formats |
|--------|---------|
| Photos | JPG, PNG, GIF, WebP, HEIC (Chrome 105+), AVIF, BMP, SVG, TIFF |
| Videos | MP4, MOV, WebM, M4V, OGG, AVI, MKV |

---

## 🖼️ Layout

```
[ small/med ]   [ small/med ]   [ small/med ]   ← top row
        [ XL frame ]   [ XL frame ]             ← center anchors
[ small/med ]   [ small/med ]   [ small/med ]   ← bottom row
```

Frame styles and sizes are randomized on each folder load, so the spread always looks a little different.

---

## 🌐 Fonts & Offline Use

Fonts load from Google Fonts on first run (internet required). After that they are cached by the browser and the gallery works **fully offline**.

---

## 🛠️ Customization

All settings are at the top of the `<script>` block:

| Variable | Default | Description |
|----------|---------|-------------|
| `CFG.MAX_SLOTS` | `8` | Number of frames shown at once |
| `CFG.CYCLE_INTERVAL` | `9500` | Ms between photo swaps |
| `CFG.FADE_MS` | `1400` | Fade transition duration (ms) |
| `CFG.STAGGER_MS` | `310` | Delay between initial frame loads |
| `CFG.PARTICLE_COUNT` | `24` | Number of floating background particles |

Frame positions, rotations, and forced sizes are defined in `SLOT_CONFIGS`.

---

## 📄 License

Free to use, modify, and share for personal use. Please don't remove the private-memorial note — it's a reminder that your memories stay yours.
