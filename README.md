<div align="center">

# ✦ NOTA

**A minimal, elegant note-taking app for thoughts, goals, ideas & tasks**

![Version](https://img.shields.io/badge/version-1.0.3-e8c97a?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-c4734a?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-7a9e7e?style=flat-square)
![Built with](https://img.shields.io/badge/built%20with-Electron-8a9abf?style=flat-square)

<br/>

![NOTA Screenshot](https://github.com/AceAnomDev/nota-app/blob/main/main/screenshot.png)

</div>

---

## ✦ About

NOTA is a distraction-free desktop app to capture everything that matters — notes, goals, ideas, and tasks — wrapped in a dark editorial aesthetic. No accounts, no cloud, no noise. Your data stays local.

---

## ✦ Features

| | |
|---|---|
| 📝 **Notes** | Free-form writing for thoughts and records |
| 🎯 **Goals** | Track progress with a visual progress bar |
| 💡 **Ideas** | Capture concepts before they slip away |
| ✅ **Tasks** | Checklist-based task management |
| 🏷️ **Tags** | Organize entries with custom tags |
| 📌 **Pin** | Keep important entries at the top |
| 🔍 **Search** | Instant full-text search across all entries |
| 💾 **Local storage** | All data saved locally, no account needed |
| ⌨️ **Shortcuts** | `Ctrl/Cmd + N` to create a new entry |

---

## ✦ Download

Go to [**Releases**](../../releases/latest) and download the installer for your platform.

| Platform | File | Instructions |
|----------|------|-------------|
|  Windows | `.exe` | Run the installer and follow the steps |
| 🍎 macOS | `.dmg` | Open and drag NOTA to Applications |
| 🐧 Linux | `.AppImage` | `chmod +x NOTA-*.AppImage` then run |

---

## ✦ Development

```bash
# Clone the repo
git clone https://github.com/AceAnomDev/nota-app.git
cd nota-app

# Install dependencies
npm install

# Run in development mode
npm start
```

### Build installers locally

```bash
npm run build:win    # → Windows .exe
npm run build:mac    # → macOS .dmg
npm run build:linux  # → Linux .AppImage
```

### Release a new version

Push a tag — GitHub Actions builds everything automatically:

```bash
git tag v1.0.0
git push origin v1.0.0
```

Installers for all three platforms will appear in **Releases** in ~10 minutes.

---

## ✦ Tech Stack

- [Electron](https://www.electronjs.org/) — cross-platform desktop shell
- [electron-builder](https://www.electron.build/) — packaging & installers
- [GitHub Actions](https://github.com/features/actions) — CI/CD pipeline
- Vanilla HTML / CSS / JS — zero framework dependencies
- `localStorage` — simple, reliable local persistence

---

## ✦ License

MIT © [AceAnomDev](https://github.com/AceAnomDev)
