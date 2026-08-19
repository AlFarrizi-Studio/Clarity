<div align="center">

<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/rics%20elements/YouTube%20Music.svg" width="300" alt="Clarity for YouTube Music" />

# Clarity — Better Lyrics Theme

**A glassmorphism theme for Better Lyrics on YouTube Music**

*Translucent dark glass, real-time blur, a floating player bar with a spinning vinyl, and cinematic word-synced lyrics.*

[![Version](https://img.shields.io/badge/version-1.0.5-1db954?style=for-the-badge)]()
[![Better Lyrics](https://img.shields.io/badge/Better%20Lyrics-theme-7aa2f7?style=for-the-badge)]()
[![Built with](https://img.shields.io/badge/built%20with-RICS-cd679b?style=for-the-badge)]()
[![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)]()

<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/1.webp">
<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/2.webp">

[Features](#-features) • [Screenshots](#-screenshots) • [Installation](#-installation) • [Theme Settings](#-theme-settings) • [Credits](#-credits)

</div>

---

## ✨ Features

### 🎛️ Floating Player Bar
- Fixed floating bar with 20px rounded corners, dark glass (`blur(28px) saturate(150%)`) and soft shadows.
- **Vinyl disc animation** — the record spins behind the album art while playing and slides out when paused.
- **4px progress bar** hugging the bottom edge of the bar; the knob appears on hover.
- **Volume slider** that expands on hover and collapses when idle.
- Useless buttons hidden (expand menu, player-page toggle, back/down).
- Responsive at 1100px and 800px breakpoints.

### 🖥️ Fullscreen Media Control
- Bar is hidden by default in fullscreen; it appears when hovering the Better Lyrics dock.
- Stays open while the cursor is over the bar, then auto-hides with a smooth delay.
- Transparent + blurred background; layout mirrors the non-fullscreen bar 1:1.

### 🎤 Word-Synced Lyrics (Better Lyrics)
- **Layout placement**: lyrics on the left / right / center.
- **Directional animations**: slide-in / slide-out from the sides, flip for center placement.
- **Dedicated typography**: Figtree (lyrics), Lexend (translations), Albert Sans (romanization).
- Visual cleanup for romanization and translation lines.

### 🧊 Glass UI Across the App
- **Popup menus**, **share dialog**, **search + suggestions**, and the **sidebar drawer** — all frosted glass with matching blur.
- **Custom YouTube Music logo** (SVG) with hover zoom.
- Notification toasts hidden for a clean look.

### 🗂️ Player Page
- Album cover with a 2rem corner radius.
- Non-fullscreen: **grid layout** — cover on the left, tabs centered below the cover, lyrics on the right.
- **16:9 video mode** with a proper host box.
- **Custom icon tabs** (Up Next, Lyrics, Comments, Related) with pill styling + a selection ring.

---

## 📸 Screenshots

<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/3.png">
<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/4.png">
<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/5.png">
<img src="https://raw.githubusercontent.com/AlFarrizi-Studio/Clarity-Theme/refs/heads/main/images/6.png">

---

## 📦 Installation

**Via the Better Lyrics Marketplace (recommended)**
1. Open the **Better Lyrics** extension → **Marketplace / Themes**.
2. Search for **Clarity** → **Install**.
3. The theme is applied automatically.

**Manual (Custom Style)**
1. Copy the contents of `Clarity_Better_Lyrics.scss` (compile to CSS if needed).
2. Better Lyrics → Settings → **Custom CSS** → paste.
3. Hard refresh (`Ctrl + Shift + R`).

---

## ⚙️ Theme Settings

| Setting | Type | Default | Description |
|---|---|---|---|
| `placement` | dropdown | `left` | Lyrics placement: `left` / `right` / `center` |
| `album-cover-border-radius` | textfield | `2rem` | Album cover corner radius |
| `lyrics-animation-speed` | textfield | `1.6s` | Lyric line animation speed |
| `center-animation-speed` | textfield | `1.2s` | Animation speed for center placement |
| `cover-vinyl-animation-speed` | textfield | `0.7s` | Vinyl / cover slide animation speed |
| `bar-bg` | textfield | `rgba(14,14,18,0.86)` | Player bar background color |
| `bar-radius` | textfield | `20px` | Player bar corner radius |
| `accent` | textfield | `#1db954` | Accent color |

---

## 🎨 Design Tokens

| Token | Value | Usage |
|---|---|---|
| `$bar-bg` | `rgba(14, 14, 18, 0.86)` | Glass surface |
| `$bar-radius` | `20px` | Player bar radius |
| `$surface-1/2/3` | white `6% / 10% / 16%` | Hover / active layers |
| `$border-subtle` | white `8%` | Hairline borders |
| `$text-1/2/3` | white `100% / 70% / 45%` | Text hierarchy |
| Blur | `blur(28px) saturate(150%)` | Frosted glass |

---

## 🗂️ Repository Structure

```
Clarity-Theme/
├── style.rics   # Theme source (RICS)
├── metadata.json                # Theme metadata (marketplace)
├── settings.json                # User-configurable settings
├── .gitignore
├── .gitattributes
├── README.md
└── images/
    ├── 1.webp … 2.webp          # Screenshots (animated webp)
    ├── 3.png … 6.png            # Screenshots (png)
    └── rics elements/
        ├── YouTube Music.svg    # Custom logo
        └── Vinly Disc.png       # Vinyl disc asset
```

---

## 🙏 Credits

- **Author** — Al Farrizi ([AlFarrizi-Studio](https://github.com/AlFarrizi-Studio))
- Built for [Better Lyrics](https://betterlyrics.org)
- Fonts: [Figtree](https://fonts.google.com/specimen/Figtree) • [Lexend](https://fonts.google.com/specimen/Lexend) • [Albert Sans](https://fonts.google.com/specimen/Albert+Sans) • [Inter](https://fonts.google.com/specimen/Inter)

---

## 📄 License

MIT — free to use, modify, and redistribute with credit.

---

<div align="center">

**Made with ❤️ by Al Farrizi**

*If you like this theme, give it a ⭐!*

</div>
