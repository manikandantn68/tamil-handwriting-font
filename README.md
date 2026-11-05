# M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI

**Free, open-source handwritten Tamil font** with Tamil-Brahmi inspired letters. Formats: **TTF, OTF, WOFF**. Works on Windows, macOS, Linux, Android, iOS and websites.

**Author:** M. Manikandan - creator and designer, Kumbakonam, Tamil Nadu, India
**Enquiries:** 9787091093

[![Download](https://img.shields.io/badge/Download-Latest%20Release-6B3FA0?style=for-the-badge)](https://github.com/manikandantn68/tamil-handwriting-font/releases/latest)
[![License: OFL](https://img.shields.io/badge/License-SIL%20OFL%201.1-blue?style=for-the-badge)](LICENSE)

**Quick links:** [Preview](#1-preview) · [Installation](#2-installation) · [Checking](#3-checking) · [CSS](#4-css-for-websites) · [Typing chart](#typing-chart) · [FAQ](#faq)

---

## 1. Preview

<p align="center">
  <img src="images/preview.png" alt="M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI font preview" width="100%">
</p>

### All Tamil letters in the font

<p align="center">
  <img src="images/all-letters.png" alt="All 34 Tamil letters with Unicode code points" width="100%">
</p>

---

## 2. Installation

### Step 1: Download

**[Download the latest release](https://github.com/manikandantn68/tamil-handwriting-font/releases/latest)** and unzip `M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI-all-formats.zip`.

Or clone the repository:

```bash
git clone https://github.com/manikandantn68/tamil-handwriting-font.git
```

Font files are in the `desktop/` folder (TTF and OTF) and the `web/` folder (WOFF).

> Install **only one** of the TTF or OTF files. They share the same name.
> If you installed an older version, uninstall it first.

### Step 2: Install on your system

| System | How to install |
|---|---|
| **Windows 10/11** | Right-click `M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI.ttf` and choose **Install** (or **Install for all users**). Restart your apps. |
| **macOS** | Double-click the `.ttf` file and click **Install Font** in Font Book. |
| **Linux** | Copy the `.ttf` to `~/.local/share/fonts/`, then run `fc-cache -f`. |
| **Android** | Android has no system-wide font install. Import the `.ttf` in apps that allow custom fonts (Canva, PicsArt, WPS Office, etc.). |
| **iPhone / iPad** | Install with a font app such as AnyFont or iFont, then pick it in Pages or Keynote. |

---

## 3. Checking

### Check that the font is installed

- **Windows:** Settings → Personalization → Fonts → search for `MANIKANDAN`.
- **macOS:** open Font Book and search for `MANIKANDAN`.
- **Linux:** run `fc-list | grep -i MANIKANDAN`.

### Check that it works

1. Restart Word, or any app you use.
2. Pick **M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI** from the font list.
3. Type the keys below. You should see your handwriting, not Arial.

<p align="center">
  <img src="images/check-example.png" alt="Typing check example" width="100%">
</p>

| You type | Result |
|---|---|
| `kasatapama` | க அ ஸ அ ட அ ப அ ம அ (in your handwriting) |
| `nawalLzv` | ந ன ல ள ழ வ |
| `aAiIuU` | அ ஆ இ ஈ உ ஊ |

If you still see a normal font: restart the app (or the computer), make sure only one copy is installed, and check that the correct font name is selected.

### Check in a browser

Download the repo and open `web/example.html` in your browser. It loads the WOFF font and shows sample text.

---

## 4. CSS for websites

### Option A: host the font files yourself

Copy `web/M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI-TTF.woff` to your website, then add:

```css
@font-face {
  font-family: "M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI";
  src: url("M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI-TTF.woff") format("woff");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

.tamil-handwriting {
  font-family: "M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI", sans-serif;
  font-size: 48px;
}
```

### Option B: load it from the CDN (no download needed)

```css
@font-face {
  font-family: "M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI";
  src: url("https://cdn.jsdelivr.net/gh/manikandantn68/tamil-handwriting-font@main/web/M.MANIKANDAN-ANCIENT-TAMIL-BRAHMI-TTF.woff") format("woff");
  font-display: swap;
}
```

### Use it in HTML

```html
<p class="tamil-handwriting">கசடதபறம நனணலளழவ</p>
```

---

## Typing chart

You can type with a Tamil keyboard, or with an **English keyboard** using this chart:

<p align="center">
  <img src="images/typing-chart.png" alt="English keyboard typing chart" width="100%">
</p>

Other Latin letters map to the closest-sounding Tamil letter: `b B f F P` = ப, `d D` = ட, `g G q x X` = க, `j C` = ச, `H` = ஹ, `M` = ம, `V` = வ, `Z` = ழ.

## Character coverage

| Character set | Covered |
|---|---|
| Tamil (U+0B80-0BFF) | 34 of 128 |
| Brahmi (U+11000-1107F) | 31 of 128 |
| Basic Latin (U+0020-007E) | 95 of 95 |
| Latin-1 Supplement | 78 of 96 |
| Geometric Shapes | 17 of 96 |

**Not yet drawn:** the letter ஜ, Tamil vowel signs (ா ி ீ ு ூ ெ ே ை ொ ோ ௌ) and the pulli (்). Words that need these show them in a fallback font.

## FAQ

**Is it free for commercial use?** Yes. The SIL Open Font License allows commercial use, modification and redistribution. You may not sell the font file by itself.

**Why do some Tamil words look wrong?** Vowel signs and the pulli are not drawn yet, so they appear in another font.

**Why does it not show in WhatsApp, Notepad or my browser?** Those apps use their own fonts. Use the font in Word, Canva or another design app, or use the CSS above on a website.

**Can I add the missing letters?** Yes. Draw them on the template (`oldtamil.pdf`), then open an issue or pull request.

## Contributing

1. Fork the repo.
2. Draw the missing glyphs on the template.
3. Open a pull request with your scan or photo.

## Author

**M. Manikandan** - creator and designer, Kumbakonam, Tamil Nadu, India
Enquiries: **9787091093**

## License

Copyright 2026 M. Manikandan.
SIL Open Font License 1.1. See [LICENSE](LICENSE).

## Keywords

Tamil font, Tamil handwriting font, free Tamil font, Tamil Brahmi font, ancient Tamil font, handwritten Tamil, Tamil TTF, Tamil OTF, Tamil WOFF, open source Tamil font, Tamil typography.
