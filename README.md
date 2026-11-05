# Tamil Handwriting Font (MyTamilFont)

## Author

**M. Manikandan** -  Kumbakonam, Tamil Nadu, India

For any enquiries, contact: **9787091093**

**Free, open-source handwritten Tamil font** with Tamil-Brahmi inspired letters.
Download **TTF, OTF and WOFF** for Windows, macOS, Linux, Android, iOS and websites.
Licensed under the **SIL Open Font License 1.1** - free for personal and commercial use.


---

## Features

- Hand-drawn Tamil letters: vowels (அ ஆ இ ஈ உ ஊ எ ஏ ஐ ஒ ஓ ஔ), ௐ, and consonants (க ங ச ஞ ட ண த ந ன ப ம ய ர ற ல ள ழ வ ஷ ஸ ஹ)
- Same letters on the **Brahmi** Unicode block (U+11000)
- Full **Basic Latin** coverage so the font previews and types on any keyboard
- Drawn digits, punctuation and common geometric shapes
- Formats: **TTF, OTF, WOFF**
- Open source: edit, extend and redistribute under the OFL

## Character coverage

| Character set | Covered |
|---|---|
| Tamil (U+0B80-0BFF) | 34 of 128 |
| Brahmi (U+11000-1107F) | 31 of 128 |
| Basic Latin (U+0020-007E) | 95 of 95 |
| Latin-1 Supplement | 78 of 96 |
| Geometric Shapes | 17 of 96 |

**Not yet drawn:** the letter ஜ, Tamil vowel signs (ா ி ீ ு ூ ெ ே ை ொ ோ ௌ) and the pulli (்).
Words that need these will show them in a fallback font. Contributions welcome!

## Installation

| System | Steps |
|---|---|
| **Windows 10/11** | Right-click the `.ttf` file, choose **Install**. Restart your apps. |
| **macOS** | Double-click the `.ttf` file, choose **Install Font**. |
| **Linux** | Copy to `~/.local/share/fonts/`, then run `fc-cache -f`. |
| **Android** | Import the `.ttf` in apps that allow custom fonts (Canva, PicsArt, WPS Office, etc.). |
| **iPhone / iPad** | Install with a font app such as AnyFont or iFont, then pick it in Pages or Keynote. |

Install **only one** of the TTF or OTF files, since they share the same name.

## Typing

You can type with a Tamil keyboard (the real Tamil Unicode characters are mapped), or with an **English keyboard**:

| Keys | Letters |
|---|---|
| `a A i I u U` | அ ஆ இ ஈ உ ஊ |
| `e E Y` | எ ஏ ஐ |
| `o O W` | ஒ ஓ ஔ |
| `k K c J` | க ங ச ஞ |
| `t N T` | ட ண த |
| `n w p m y` | ந ன ப ம ய |
| `r R l L` | ர ற ல ள |
| `z v` | ழ வ |
| `S s h` | ஷ ஸ ஹ |
| `Q` | ௐ |

Other Latin letters map to the closest-sounding Tamil letter: `b B f F P` = ப, `d D` = ட, `g G q x X` = க, `j C` = ச, `H` = ஹ, `M` = ம, `V` = வ, `Z` = ழ.

Digits, punctuation and shapes are simple drawn symbols in a matching marker style.

## Use on a website

```css
@font-face {
  font-family: "MyTamilFont";
  src: url("MyTamilFont-TTF.woff") format("woff");
}

.tamil-text {
  font-family: "MyTamilFont", sans-serif;
}
```

## FAQ

**Is it free for commercial use?** Yes. The SIL Open Font License allows commercial use, modification and redistribution. You may not sell the font file by itself.

**Why do some Tamil words look wrong?** Vowel signs and the pulli are not drawn yet, so they appear in another font.

**Can I add the missing letters?** Yes. Draw them on the template (`oldtamil.pdf`), then open an issue or pull request.

## Contributing

1. Fork the repo.
2. Draw the missing glyphs on the template.
3. Open a pull request with your scan or photo.

## License

Copyright 2026 M. Manikandan.
SIL Open Font License 1.1. See [LICENSE](LICENSE).

## Keywords

Tamil font, Tamil handwriting font, free Tamil font, Tamil Brahmi font, handwritten Tamil, Tamil TTF, Tamil OTF, Tamil WOFF, open source Tamil font, Tamil typography.
