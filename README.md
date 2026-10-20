# GlyphForge Font - Next-Gen Script & Legacy Font Converter

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-success?style=for-the-badge&logo=github)](https://dmstyles.github.io/glyphforge-font/)
[![Offline Ready](https://img.shields.io/badge/Offline-100%25%20Ready-blue?style=for-the-badge)](https://dmstyles.github.io/glyphforge-font/)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

**GlyphForge Font** is a modern, high-performance, 100% client-side dual-script font converter:
- 🇱🇰 **Sinhala Unicode ➔ FM Legacy Fonts** (FM Abhaya, FM Abhaya Bold, FM Derana, FM Malithi, FM Bindumathi)
- 🇮🇳/🇱🇰 **Tamil Unicode ➔ Bamini Legacy Font (பாமினி)**
- ⚡ **Natural Singlish Phonetic Typing Engine** (Type Sinhala using English letters with real-time conversion)
- 🔄 **Bidirectional Conversion** (Legacy FM / Bamini ➔ Modern Unicode)

🌐 **Live Web App:** [https://dmstyles.github.io/glyphforge-font/](https://dmstyles.github.io/glyphforge-font/)

Designed specifically for graphic designers, video editors, typesetters, and office professionals who copy-paste Sinhala and Tamil text into **Adobe Photoshop**, **Illustrator**, **InDesign**, **Premiere Pro**, **CorelDraw**, or **Microsoft Word** where modern Unicode complex ligatures break or fail to render.

---

## 🌟 Key Features

### 1. ⚡ Natural Singlish Phonetic Typing
- Type Sinhala phonetically using standard English letters (e.g., `mama gedara yanawa` ➔ `මම ගෙදර යනවා`).
- Word-by-word conversion triggered naturally on **Space**, **Enter**, or **Punctuation** (`. , ! ?`).
- Real-time golden suggestion badge previews the converted word before pressing Space.
- Automatic phonetic mapping for vowels (`ae` ➔ `ඇ`, `aae` ➔ `ඈ`), consonants (`d` ➔ `ද`, `D` ➔ `ඩ`, `th` ➔ `ත`, `t` ➔ `ට`), and conjuncts (`kra` ➔ `ක්‍ර`, `kya` ➔ `ක්‍ය`, `ksha` ➔ `ක්ෂ`, `shri` ➔ `ශ්‍රී`).
- Automatic verb suffix handling (`-nawa` ➔ `...නවා`, `-nawada` ➔ `...නවද`, `-da` ➔ `...ද`).
- Toggle Singlish typing on/off anytime with **`Ctrl + Space`**.
- Automatic conversion when pasting Singlish text paragraphs.
- Built-in **Singlish Key Guide & Cheat Sheet** modal for fast reference.

### 2. 🇮🇳/🇱🇰 Tamil to Bamini Font Converter
- Full conversion of Tamil Unicode text (e.g., `நாணயத் திணைக்களம்`) into the standard legacy **Bamini** ASCII format (`ehzaj; jpizf;fsk;`).
- Reverse conversion (Bamini ➔ Tamil Unicode) with 100% round-trip accuracy.
- Bundled offline `Bamini.ttf` TrueType font for in-browser visual font preview.

### 3. 🇱🇰 Sinhala Unicode to FM Fonts
- Multi-stage ligature mapper resolving UCSC legacy ordering bugs (`ක්‍ෂේත්‍රය`, `ශ්‍රී ලංකා`, `ද්‍රව්‍ය`, `ව්‍යාපාර මුදල් දෙපාර්තමේන්තුව`, `බුද්ධ`).
- Supports **FM-Abhaya**, **FM-Abhaya Bold**, **FM-Derana**, **FM-Malithi**, and **FM-Bindumathi**.

### 4. 🧠 Smart Script Auto-Detection
- Automatically detects Tamil vs. Sinhala script upon typing or pasting and instantly configures the appropriate font settings.

### 5. 🖥️ Flexible Workspaces
- **Standard Tabbed View:** Switch between Unicode and Legacy tabs with 1 click.
- **Dual Split View:** Side-by-side editing with live real-time synchronization.

### 6. 👁️ Visual Font Preview & Raw ASCII Mode
- Preview how text will appear in genuine FM / Bamini fonts before copying.
- Switch to Raw ASCII to inspect keyboard mappings.

### 7. 💾 One-Click Font Downloader
- Download authentic `.ttf` font files (`Bamini.ttf`, `FM_AB__.TTF`, `FM_DERAN.TTF`, `FM_MALIT.TTF`, `FM_BINDU.TTF`) directly from the browser to install on Windows.

---

## 🎨 How to Use in Photoshop, Illustrator & Word

### For Tamil (Bamini):
1. In GlyphForge, switch to **Tamil (Bamini Font)** or paste your Tamil text (e.g., `நாணயத் திணைக்களம்`).
2. Click **"Copy Text"** (or switch to Legacy tab and copy `ehzaj; jpizf;fsk;`).
3. Open **Photoshop / Illustrator / Word**, create a text layer, and press **Ctrl + V**.
4. Set the font family to **Bamini**.
5. All Tamil characters render with clean, authentic Bamini ligatures!

### For Sinhala (FM Abhaya):
1. In GlyphForge, switch to **Sinhala (FM Fonts)** and type or paste your Sinhala text (e.g., `ව්‍යාපාර මුදල් දෙපාර්තමේන්තුව` or in Singlish `vyaapaara mudhal dhepaarthamenthuva`).
2. Click **"Copy Text"**.
3. Open **Photoshop / Illustrator / Word** and press **Ctrl + V**.
4. Set the font family to **FM-Abhaya** (or FM-Derana).
5. All Sinhala characters render with flawless ligatures!

---

## 🚀 Local Offline Usage

GlyphForge Font is 100% self-contained with no external CDN or internet dependencies required.

- **Direct Open:** Double-click **`start.bat`** or open **`index.html`** in any web browser.
- **Local Server:** Double-click **`start-server.bat`** or run:
  ```bash
  node server.js
  ```
  The app will open at `http://localhost:3000`.

---

## 📄 License

MIT License. Free to use for personal and commercial design projects.
