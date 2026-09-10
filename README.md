<div align="center">

# ✦ Kept.

**A quiet, permanent shelf for the internet worth remembering.**

A beautiful personal link library & bookmark manager —
single file, zero setup, no account, and your data never leaves your browser.

[![License: MIT](https://img.shields.io/badge/License-MIT-D9481F.svg)](LICENSE)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-Vanilla%20JS-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Storage](https://img.shields.io/badge/Storage-localStorage-211B12?logo=databricks&logoColor=white)](#-how-your-data-is-stored)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2EA44F.svg)](#-contributing)

**Built by [NIKHIL TOMAR](https://github.com/nikhiltomar2712)** · [@nikhiltomar2712](https://github.com/nikhiltomar2712)

</div>

---

## 📖 About

**Kept.** is a modern bookmark manager inspired by the calm of Notion, the visual cards of
Pinterest, and the simplicity of Linktree — but built as **one single HTML file**.

No build step. No install. No sign-up. Just open it and start saving the sites you
don't want to lose — each one with a **title, a purpose ("This site is for…"), a logo,
and a cover banner**, laid out as beautiful editorial cards.

---

## ✨ Features

### 🔖 Saving & Editing
- Save any website with **URL, title, description, logo & banner image**
- Add images by **pasting a URL** or **uploading a file** (auto-compressed in the browser so localStorage stays happy)
- One-click **"Use the site's favicon"** shortcut for logos
- No images? Every card still looks designed — **procedurally generated SVG covers** (dots, waves, rings, lines) derived from each site's title & URL
- Edit any saved site anytime via a smooth sliding side panel

### 🗂 Organizing
- 🔍 **Instant search** across titles, descriptions, URLs and tags
- 🏷 **Tags / categories** with filter chips and live counts (up to 6 per link)
- ⭐ **Favorites tab** — star important sites and browse them separately
- ↕️ **Drag & drop reordering** — works even while filters are active
- 🌗 **Dark mode / light mode** toggle (remembers your choice, respects system preference)

### 🛟 Safety & Data
- 💾 **Permanent localStorage persistence** — nothing ever leaves your device
- ✂️ **Two-step delete** (click once → "Sure?") plus a **5-second Undo** toast
- 📦 **Export your entire library as JSON** with one click
- 🎁 **4 example links** seeded on first run — yours to edit or delete

### 🎨 Design
- Warm **paper & ink** editorial aesthetic with Fraunces + Sora + JetBrains Mono typography
- Soft shadows, rounded corners, staggered card animations
- Custom empty states, live count-up stats, subtle paper grain texture
- **Fully responsive** — from mobile to ultra-wide desktop

---

## 🚀 Getting Started

### Run locally (10 seconds)

```bash
# 1. Clone the repo
git clone https://github.com/nikhiltomar2712/kept.git

# 2. Open the file
cd kept
```

Then just **double-click `index.html`** — that's it. No server, no build, no dependencies to install.

> Optional: serve it locally with `npx serve` or the *Live Server* VS Code extension.

### Deploy it free

| Platform | How |
|---|---|
| **GitHub Pages** | Repo → Settings → Pages → Deploy from `main` branch |
| **Netlify** | Drag & drop the folder onto [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | `vercel` in the project folder |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|:---:|---|
| `/` | Focus the search bar |
| `n` | Save a new link |
| `esc` | Close the add/edit panel |

---

## 🗄 How Your Data Is Stored

- Everything lives in your browser's **localStorage** (keys: `kept.sites.v1`, `kept.theme`)
- Uploaded images are **downscaled & compressed to JPEG in-browser** (banner max 1280px, logo max 512px) before saving
- **Nothing is sent to any server** — there are no analytics, no trackers, no accounts
- Clearing your browser data will erase your library — use **Export JSON** for backups 💾

---

## 🧰 Tech Stack

- **HTML + CSS + Vanilla JavaScript** — zero frameworks, zero build tools
- **Lucide Icons** (CDN)
- **Google Fonts** — Fraunces, Sora, JetBrains Mono
- **localStorage** for persistence
- **Canvas API** for client-side image compression
- Procedural **SVG** cover generation

---

## 📁 Project Structure

```
kept/
├── index.html    # The entire app — UI, styles & logic
├── README.md     # You are here
└── LICENSE       # MIT
```

---

## 🗺 Roadmap

- [ ] Import from exported JSON
- [ ] Optional cloud sync (Firebase / Supabase)
- [ ] Folder / collections view
- [ ] Favicon + Open Graph auto-fetch on save
- [ ] Share a read-only public library page

---

## 🤝 Contributing

Contributions, ideas and bug reports are welcome!

1. Fork the repo
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

<div align="center">

### 👤 Author

# NIKHIL TOMAR

[![GitHub](https://img.shields.io/badge/GitHub-@nikhiltomar2712-181717?style=for-the-badge&logo=github)](https://github.com/nikhiltomar2712)

If you find **Kept.** useful, please consider giving it a ⭐ — it helps a lot!

**"A quiet, permanent shelf for the internet worth remembering."**

</div>
````
