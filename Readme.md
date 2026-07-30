
<p align="center">
  <img src="build/Quran-app-logo.png" alt="Quran Dastoor e Hayat" width="128">
</p>

<h1 align="center">قرآن دستور حیات — Quran Dastoor e Hayat</h1>

<p align="center">
  <strong>ایک مکمل، آف لائن، اور خوبصورت قرآن ڈیسک ٹاپ ریڈر</strong><br>
  <em>A complete, offline, and beautiful Quran desktop reader for Windows, macOS & Linux.</em>
</p>

<p align="center">
  <a href="https://github.com/mtaha686/qurran-desktop/releases">
    <img src="https://img.shields.io/github/v/release/mtaha686/qurran-desktop?label=version&color=2ea44f" alt="Release">
  </a>
  <a href="https://github.com/mtaha686/qurran-desktop/issues">
    <img src="https://img.shields.io/github/issues/mtaha686/qurran-desktop?color=d93025" alt="Issues">
  </a>
  <a href="https://github.com/mtaha686/qurran-desktop/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-GPL--3.0-blue" alt="License">
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20|%20macOS%20|%20Linux-lightgrey" alt="Platform">
</p>

---

## 🌟 Overview

**Quran Dastoor e Hayat (قرآن دستور حیات)** is a fully offline, cross-platform desktop Quran application built with Electron & React. It brings together authentic Quranic text, multiple Urdu translations, detailed tafaseer, a comprehensive dictionary compiled over 15 years, thematic indexes, and bookmarked study tools — all in one beautifully crafted interface.

> **آف لائن | مفت | مکمل**

---

## ✨ Key Features

### 📖 Quran Reader
- All **114 Surahs** with **6236 verses** in authentic IndoPak script
- Multiple reading modes: Arabic only, Urdu only, side-by-side, or stacked
- View by **Surah** or **Juz (Para)** — all 30 ajza
- **Surah order** toggle: Mushafi (standard) or Nuzuli (revelation order per Imam Sadiq narration)
- Continuous/flow layout for a mushaf-like reading experience
- **Last-read position** auto-saved and restored
- **Zoom controls** (`Ctrl +`, `Ctrl -`, `Ctrl 0`)

### 📜 Urdu Translations
- **Fateh Muhammad Jalandhari** — classic Urdu translation (public domain)
- **Balagh-ul-Quran (بلاغ القرآن)** — Urdu translation by Al-Kauthar
- **Junagarhi** Urdu translation
- Switch between translations instantly

### 📚 Tafaseer (Commentaries)
- **Tafsir Al-Kauthar (Balagh-ul-Quran)** — the app's own Al-Kauthar tafaseer
- **Bayan ul Quran** by Dr. Israr Ahmed
- **Multi-tab tafsir viewer** — compare multiple tafaseer for the same ayah
- Surah introductions (تعارف) with detailed background context

### 📗 Dictionary — قاموس القرآن لغات
- **~44,000+ Arabic words** with Urdu meanings
- Compiled over **15 years** by **Mufti Sheikh Sajjad Hussain**
- Real-time search with diacritics-insensitive matching
- Browse mode with infinite scroll
- **Word-by-word lookup**: Click any word in any ayah for instant dictionary meaning
- Right-click context menu integration

### 📘 Al-Kauthar Books Collection
- **مضامین القرآن (Mazameen ul Quran)** — Thematic index of Quranic topics with 3-level hierarchical tree
- **قرآنی دستور حیات ۳ (Dastoor e Hayat)** — 9 chapters of Quranic life guidance
- Accordion navigation with full-text search

### 🔍 Powerful Search
- Unified search across: Quran Arabic text, Urdu translations, Dictionary, Mazameen, and Dastoor Hayat
- **Full-text search** powered by SQLite FTS5
- **Diacritics-insensitive** Arabic search (auto-strips harakaat)
- Search results with highlighted matches
- **Batch selection** of multiple ayahs from search results
- Export selected ayahs to diary or clipboard

### 🎧 Audio Recitation
- Per-ayah recitation playback
- Reciters: **Abdul Basit** (Mujawwad & Murattal)
- Audio from EveryAyah.com CDN
- **Audio caching** for offline listening
- **Word-by-word audio** support (77,000+ word audio files)
- **Auto-advance** to next ayah + reader sync

### 🔖 Bookmarks & Notes
- Ayah bookmarks with optional personal notes
- Surah bookmarks (favorite surahs)
- Bookmarks panel with navigation

### 📓 Diary System (یاداشت)
- Full diary/notes system (like Evernote for the Quran)
- Create color-coded notes with titles
- Attach multiple ayahs to notes
- Add free-form text blocks
- Inline editing

### 📤 Export
- Export surahs to **PDF**, **DOCX** (Word), or **TXT**
- Export diary notes to the same formats
- Include/exclude Arabic text and Urdu translation
- **Copy to clipboard** with formatting
- **Print support**

### 🎨 Customization
- **Night mode** for comfortable reading in low light
- **3 Themes**: Sepia (سپیہ), Paper (صاف), Slate (سلیٹ)
- **5 Arabic fonts**: PDMS Saleem, Scheherazade New, KFGQPC Uthman Taha Naskh, Muhammadi Quranic, My Font Mohammad1
- **3 Urdu fonts**: Jameel Noori Nastaleeq, Jameel Noori Nastaleeq Kasheeda, Nafees Naskh
- Adjustable font size (8–72pt) independently for Arabic and Urdu
- Switch translations on the fly

### 🌐 Fully Offline
- All text data, fonts, and resources bundled in the app
- **No internet required** after installation
- Audio streaming is optional (with offline caching)

---

## 🖥️ Screenshots

> *(Add screenshots here — reader view, tafsir panel, dictionary, search, settings, etc.)*

---

## ⚡ Tech Stack

| Layer | Technology |
|---|---|
| Desktop Shell | [Electron 33](https://www.electronjs.org/) |
| UI Framework | [React 18](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/) |
| Build Tool | [Vite 5](https://vitejs.dev/) via [electron-vite](https://electron-vite.org/) |
| State Management | [Zustand 5](https://github.com/pmndrs/zustand) |
| Database | [SQLite](https://www.sqlite.org/) via [better-sqlite3](https://github.com/WiseLibs/better-sqlite3) |
| Search | SQLite FTS5 (full-text search) |
| Export | PDF, DOCX ([docx](https://docx.js.org/)), TXT |
| Icons | [Lucide React](https://lucide.dev/) |
| Packaging | [electron-builder](https://www.electron.build/) |

---

## 📦 Download

Get the latest release for your platform:

| Platform | File |
|---|---|
| **Windows** (x64) | `Quran Dastoor e Hayat-{version}-Windows-Setup.exe` |
| **macOS** (Intel) | `Quran Dastoor e Hayat-{version}-macOS-x64.dmg` |
| **macOS** (Apple Silicon) | `Quran Dastoor e Hayat-{version}-macOS-arm64.dmg` |
| **Linux** (AppImage) | `Quran Dastoor e Hayat-{version}-Linux-x86_64.AppImage` |
| **Linux** (Debian/Ubuntu) | `Quran Dastoor e Hayat-{version}-Linux-amd64.deb` |
| **Linux** (Fedora/RHEL) | `Quran Dastoor e Hayat-{version}-Linux-x86_64.rpm` |

👉 **[Download Latest Release](https://github.com/mtaha686/qurran-desktop/releases)**

---

## 🚀 Installation

### Windows
1. Download the `.exe` installer
2. Run the installer (you can choose installation directory)
3. Launch from Start Menu or Desktop shortcut

> Requires **Windows 10 or later** (64-bit)

### macOS
1. Download the `.dmg` for your chip (Intel or Apple Silicon)
2. Open the `.dmg` and drag into Applications folder
3. First launch: right-click → **Open** (required once for unsigned apps)

> Requires **macOS 10.15 (Catalina)** or later

### Linux — AppImage
```bash
chmod +x Quran*.AppImage
./Quran*.AppImage
```

### Linux — Debian/Ubuntu
```bash
sudo dpkg -i Quran*Linux-amd64.deb
```

### Linux — Fedora/RHEL
```bash
sudo rpm -i Quran*Linux-x86_64.rpm
```

---

## 🔧 Build from Source

```bash
# Clone the repository
git clone https://github.com/mtaha686/qurran-desktop.git
cd qurran-desktop

# Install dependencies
npm install

# Run in development mode
npm run dev

# Build for your current platform
npm run build && npx electron-builder --win   # Windows
npm run build && npx electron-builder --mac   # macOS
npm run build && npx electron-builder --linux # Linux

# Package for specific platform
npm run package:win
npm run package:mac
npm run package:linux
```

### Database Import Scripts

The app ships with a pre-built SQLite database. To rebuild or update it:

```bash
# Import core Quran data
npm run db:import

# Fetch & apply API data (quran.com)
npm run db:fetch

# Import translations & tafaseer
npm run db:import-balagh
npm run db:import-dictionary
npm run db:import-mazameen
npm run db:import-dastoor-hayat

# Build full-text search index
npm run db:build-search
```

---

## 🗂️ Data Sources

| Data | Source |
|---|---|
| Arabic Text (IndoPak) | [Quran.com API](https://quran.com) |
| Urdu Translation (Jalandhari) | [Tanzil.net](https://tanzil.net) — public domain |
| Urdu Translation (Junagarhi) | Quran.com API (ID 54) |
| Urdu Translation (Balagh-ul-Quran) | Al-Kauthar |
| Tafsir Bayan ul Quran | Dr. Israr Ahmed |
| Tafsir Al-Kauthar | Al-Kauthar |
| Dictionary (قاموس القرآن لغات) | **Mufti Sheikh Sajjad Hussain** — 15 years of compilation |
| Mazameen & Dastoor Hayat | Al-Kauthar books |
| Audio Recitations | [EveryAyah.com](https://everyayah.com) |
| Word Audio | [Quran.com CDN](https://audio.qurancdn.com) |

---

## 🐛 Reporting Issues

If you find a bug, have a feature request, or need help:

- **GitHub Issues**: [https://github.com/mtaha686/qurran-desktop/issues](https://github.com/mtaha686/qurran-desktop/issues)
- **Email**: Muhammad Taha — [tahamuhammadi870@gmail.com](mailto:tahamuhammadi870@gmail.com)

When reporting a bug, please include:
- Your operating system and version
- App version (visible in About dialog)
- Steps to reproduce the issue
- Screenshots (if applicable)

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code follows the existing style and conventions.

---

## 📄 License

This project is **All Rights Reserved** for the Quranic content (tafaseer, dictionary, books). The source code is available for educational purposes only.

---

## 🙏 Credits

- **Mufti Sheikh Sajjad Hussain** — قاموس القرآن لغات (15 years of dedicated work)
- **Al-Kauthar** — Balagh-ul-Quran translation & tafaseer
- **Dr. Israr Ahmed** — Bayan ul Quran tafsir
- **Quran.com** & **Tanzil.net** — Quran text data
- **EveryAyah.com** — Audio recitations
- **Muhammad Taha** — App development

---

<p align="center">
  <strong>اللہم انفعنا بما علمتنا و علمنا ما ینفعنا</strong><br>
  <sub>O Allah, benefit us with what You have taught us, and teach us what will benefit us</sub>
</p>
