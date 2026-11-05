<div align="center">

# ⇲ Squish

**Compress images right in your browser — drag, shrink, download. Nothing is uploaded.**

[**→ Live demo**](https://unitenist.github.io/squish/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No backend](https://img.shields.io/badge/backend-none-17916b)
![License](https://img.shields.io/badge/License-MIT-green)

⭐ If this saved you some bandwidth, a star is appreciated!

</div>

---

## Why

Most "compress your image" sites upload your files to a server you don't control. Squish does the whole thing in your browser with the Canvas API — your images never leave your device, and there are no file-size limits or sign-ups.

## ✨ Features

- 📂 **Drag & drop** one or many images (JPG, PNG, WebP)
- 🎚️ **Quality slider** — see the size change live
- 🔁 **Output as WebP, JPEG or PNG** — WebP usually wins big
- 📉 **Before / after sizes** and a percent-saved badge per image
- ⬇️ **Download** each result, or all at once
- 🌓 **Light / dark theme**
- 🔒 **Private by design** — no upload, no sign-up, no backend

## 🚀 Usage

Open the [live demo](https://unitenist.github.io/squish/) and drop images in. Typical photos shrink by 70–90% at the default quality.

To run locally (single HTML file, no build step):

```bash
git clone https://github.com/unitenist/squish.git
cd squish
python3 -m http.server 8000   # then visit http://localhost:8000
```

## 🧱 How it works

Each image is drawn to a `<canvas>` and re-encoded with `canvas.toBlob(mime, quality)`. No libraries, no network — just the browser.

## 🤝 Contributing

Issues and PRs welcome — batch ZIP download, resize-on-export, or AVIF output would all be nice additions.

## 📄 License

MIT — see [LICENSE](LICENSE).
