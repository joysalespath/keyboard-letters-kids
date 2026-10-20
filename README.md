# Keyboard Letters for Kids 🧒⌨️

A simple, offline, kid-friendly keyboard learning game. A child presses any key and sees a big
picture in one of three panels while a voice says the word out loud — great for letting a toddler
safely play while you learn their letters and numbers.

**Letters A–Z** → emoji + spoken word (e.g. press **A** → 🍎 "Apple")
**Numbers 0–9** → the number + spoken name (e.g. press **5** → 5️⃣ "Five")

## Features

- **26 letters A–Z**, each with a matching emoji and spoken word
- **Numbers 0–9** with spoken names
- **Three-panel layout** — pictures appear left → middle → right, then the next one replaces the
  leftmost and keeps cycling
- **100% offline** — uses emoji instead of downloaded images, so nothing can break and there are no
  broken links or network dependencies
- **Speaks each word aloud** using the browser's built-in speech synthesis
- Single self-contained `index.html` — no build step, no dependencies

## How to run

### Option 1 — Open the file directly
Download or clone the repo, then open `index.html` in any modern browser (Chrome works best for
voice):

```bash
git clone https://github.com/joysalespath/keyboard-letters-kids.git
cd keyboard-letters-kids
open index.html        # macOS
# or just double-click index.html in your file explorer
```

Click anywhere on the page once (to enable sound), then press any letter or number.

### Option 2 — Play online (GitHub Pages)
If GitHub Pages is enabled for this repo, play it live at:
<https://joysalespath.github.io/keyboard-letters-kids/>

## Notes

- **Sound:** Browsers block audio until you interact with the page — click once, then type.
- **Voice quality:** Chrome's built-in voices tend to sound best.

## Credits

Based on the original [keyboard-letters](https://github.com/harry-wood/keyboard-letters) by
Harry Wood (released into the public domain under the Unlicense). This version replaces the
image set with offline emoji, adds numbers, and uses a three-panel cycling layout.

## License

[Unlicense](LICENSE) — public domain. Free to copy, modify, and use for any purpose.
