# Glassy Blur — YouTube Music Theme

[![Installs](https://img.shields.io/endpoint?url=https://better-lyrics-themes-api.boidu.dev/api/badge/glassy-blur)](https://github.com/ankit008-mishra/glassy-blur)
[![Rating](https://img.shields.io/endpoint?url=https://better-lyrics-themes-api.boidu.dev/api/badge/glassy-blur/rating)](https://github.com/ankit008-mishra/glassy-blur)

A refined glass-morphism userstyle for YouTube Music. Inspired by Apple Music's clean aesthetics, this theme replaces heavy UI surfaces with translucent, blurred panels that let album artwork breathe through the interface.

> **Requires [Better Lyrics](https://github.com/better-lyrics/better-lyrics)** — This theme is built for the Better Lyrics extension and leverages its lyrics engine for the full visual experience.

---

## ✨ Features

- **True Glass Morphism** — Backdrop-blur on nav bar, player bar, menus, modals, and dropdowns.
- **Unified Typography** — San Francisco Pro font family across the entire app for a native Apple-ecosystem feel.
- **BetterLyrics Integration** — Custom-tuned lyrics styling with Apple Music–inspired blur states, color transitions, and layout fixes.
- **Smooth Global Animations** — Keyframe-powered entrance animations for cards, menus, player page, sidebar, and queue items.
- **Clean Player Layout** — Consistent album-art sizing, rounded corners, and shadow depth in both standard and fullscreen modes.
- **Smart Thumbnails** — Rounded art for videos, perfect circles for artists, and square crops for playlists/albums.
- **Queue & Menu Polish** — Frosted-glass context menus, settings dialogs, share panels, and playlist add-to options.
- **Optimized Footprint** — ~90 KB of pure CSS with no SCSS dependencies or preprocessor bloat.

---

## 📦 Installation

### Method 1: Better Lyrics Theme Store (Recommended)

The easiest way to install:

1. Make sure you have the **[Better Lyrics](https://github.com/better-lyrics/better-lyrics)** browser extension installed.
2. Open the Better Lyrics extension options → **Themes** tab → **Browse Themes**.
3. Search for **"Glassy Blur"** and click **Install**.
4. Refresh YouTube Music. Done!

### Method 2: Direct Install from URL

1. Open the Better Lyrics extension options → **Themes** tab.
2. Click **Install from URL**.
3. Paste your theme's GitHub repo URL:
   ```
   https://github.com/ankit008-mishra/glassy-blur
   ```
4. Click Install and refresh YouTube Music.

### Method 3: Manual Install (Stylus)

If you prefer using Stylus or any user-style injector:

1. Install the [Stylus](https://add0n.com/stylus.html) extension for your browser.
2. Create a new style for **`music.youtube.com`**.
3. Paste the contents of **`style.css`** (from this repo).
4. Save and refresh YouTube Music.

> ⚠️ **Note:** Manual installation via Stylus will give you the visual theme, but the Better Lyrics–specific features (lyrics blur, background art, synced word highlighting) require the Better Lyrics extension to be active.

---

## 🎨 Customization

All tweakable values live at the top of the file inside the `:root` block:

| Variable | Default | Description |
|----------|---------|-------------|
| `--lucid-glass-blur` | `25px` | Master blur strength for glass panels |
| `--lucid-nav-glass-bg` | `rgba(30,30,30,0)` | Top nav background |
| `--lucid-player-glass-bg` | `rgba(20,20,20,0.2)` | Bottom player bar background |
| `--lucid-menu-dark-bg` | `rgba(30,30,30,0.35)` | Settings & profile menu bg |
| `--lucid-menu-light-bg` | `rgba(30,30,30,0.1)` | 3-dot song menu bg |
| `--lucid-video-tab-gap` | `1.3vw` | Lyrics ↔ video gap in Video tab |
| `--lucid-audio-center` | `25vw` | Center shift for square art when no lyrics |
| `--blyrics-font-size` | `3rem` / `5rem` (≥1279 px) | Lyrics font size |
| `--yt-album-size` | `500px` | Max album art size |

Edit these values directly in the CSS to personalize the theme without touching any other rule.

---

## 🖼️ Preview

[!Preview](https://raw.githubusercontent.com/ankit008-mishra/Glassyblur/refs/heads/main/images/1.png)

---

## 🧩 Compatibility

- **Browsers:** Chrome, Edge, Brave, Firefox (with standard CSS `backdrop-filter` support).
- **Extensions:** Better Lyrics (required for lyrics features), Stylus (optional for manual install).
- **BetterLyrics Version:** Minimum `2.0.5.6` recommended.

---

## 🏗️ Built With

- **Base structure** inspired by *chengggit*'s dynamic theme architecture.
- **Original concept & design** by **ankit008-mishra**.
- **Optimized & maintained** by the community.

---

## 📄 License

This project is released under the MIT License. Feel free to fork, modify, and redistribute with attribution.

---

## 🤝 Contributing

Pull requests are welcome. If you spot a broken selector after a YouTube Music update, open an issue with:
- Your browser & extension version
- A screenshot of the affected area
- The expected vs. actual behavior

---

*Enjoy your music, beautifully.*
