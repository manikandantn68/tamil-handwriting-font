
-
preview
<img width="1500" height="520" alt="1" src="https://github.com/user-attachments/assets/124569f2-f39f-49e0-bcbf-cd50f0ecf682" />
<img width="1390" height="710" alt="3" src="https://github.com/user-attachments/assets/f8027907-9e62-4c9f-b69f-717397c04edd" />
<img width="1919" height="589" alt="2" src="https://github.com/user-attachments/assets/243e099e-2358-414e-8188-1215a8cff27a" />
-

-
installation
<img width="1918" height="926" alt="1" src="https://github.com/user-attachments/assets/d3ea38d1-8993-420c-8256-3809258c5480" />
<img width="1919" height="838" alt="2" src="https://github.com/user-attachments/assets/d980584f-094c-4e52-a7e1-cb38c886daf9" />
<img width="643" height="719" alt="3" src="https://github.com/user-attachments/assets/3e3b3866-d15a-4509-97e7-67192c14f7b3" />
<img width="1919" height="1079" alt="4" src="https://github.com/user-attachments/assets/3282642d-6a32-4ebf-9181-e3e8f95e75a2" />
<img width="1928" height="1034" alt="5" src="https://github.com/user-attachments/assets/795d5b97-77be-44e0-ba0a-a0d9bb44283b" />

-

-
checking

<img width="1919" height="1081" alt="1" src="https://github.com/user-attachments/assets/54421450-8e80-4cc5-b0c3-f2f4716b84ec" />
<img width="1918" height="380" alt="2" src="https://github.com/user-attachments/assets/0f8ba325-a2e6-4f11-8357-35b2db754f9c" />
<img width="1918" height="1029" alt="3" src="https://github.com/user-attachments/assets/ff582b90-c534-45f4-b947-fa438b675f6a" />
<img width="1919" height="1029" alt="4" src="https://github.com/user-attachments/assets/8eb3fbe7-6b74-4d88-84a2-0d8ab5857e80" />
<img width="1919" height="336" alt="5" src="https://github.com/user-attachments/assets/ba9a67d7-4039-4f7c-aa7f-cc4ebb8d5bca" />



-
css
<img width="1919" height="475" alt="1" src="https://github.com/user-attachments/assets/6d6199ad-9854-4b6d-9cbc-b9aab76497b8" />
<img width="1919" height="475" alt="2" src="https://github.com/user-attachments/assets/896a5647-4ae3-4b59-94a3-08b8a895a665" />

--
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
