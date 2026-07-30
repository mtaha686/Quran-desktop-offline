
<p align="center">
<img width="125" height="125" alt="Quran-app-logo" src="https://github.com/user-attachments/assets/62ec5be2-ba9d-49e8-b96d-e21a985a3910" />
</p>

<h1 align="center">قرآن دستور حیات — Qurran Desktop</h1>

<p align="center">
  <strong>v0.1.0 (Windows)</strong><br>
  <em>A clean, offline Quran reader for your desktop — ڈیسک ٹاپ قرآن ریڈر</em>
</p>

<p align="center">
  <a href="https://github.com/mtaha686/Quran-desktop-offline/releases">
    <img src="https://img.shields.io/badge/download-Windows%20Setup-blue?style=flat-square" alt="Download">
  </a>
  <a href="https://github.com/mtaha686/Quran-desktop-offline/issues">
    <img src="https://img.shields.io/badge/report%20issues-GitHub-red?style=flat-square" alt="Issues">
  </a>
</p>

---

## Screenshots

<img width="960" alt="qurran1" src="https://github.com/user-attachments/assets/c43bb533-9a68-49f1-b5e1-ce2e6301d17b">
<img width="960" alt="qurran2" src="https://github.com/user-attachments/assets/59e2d0c3-2cf0-4b72-b087-550eea196cb3">
<img width="959" alt="qurran3" src="https://github.com/user-attachments/assets/8fb37889-e190-4fdf-8426-f8a6965b320d">
<img width="960" alt="qurran4" src="https://github.com/user-attachments/assets/0b2074da-09a3-47ec-a66f-545d58372334">
<img width="959" alt="qurran5" src="https://github.com/user-attachments/assets/1cbb6628-0b12-40f7-9bfd-896c8c0e7917">
<img width="960" alt="qurran6" src="https://github.com/user-attachments/assets/56782fc7-daa5-42e8-88d7-cfc908040127">
<img width="960" alt="qurran7" src="https://github.com/user-attachments/assets/87019e8b-a137-4e97-87ea-0dcae2fdaf61">

---

## 🌟 Overview

**Quran Dastoor e Hayat (قرآن دستور حیات)** is a fully offline, cross-platform desktop Quran application built with Electron & React. It brings together authentic Quranic text, multiple Urdu translations, detailed tafaseer, a comprehensive dictionary compiled over 15 years, thematic indexes, and bookmarked study tools — all in one beautifully crafted interface.

---

## Features

### 📖 Quran Reader
- All 114 Surahs with 6236 verses in authentic IndoPak script
- Multiple reading modes: Arabic only, Urdu only, side-by-side, or stacked
- View by Surah or Juz (Para) — all 30 ajza
- Surah order toggle: Mushafi (standard) or Nuzuli (revelation order)
- Continuous/flow layout for mushaf-like reading
- Last-read position auto-saved, zoom controls (Ctrl +, Ctrl -, Ctrl 0)

### 📜 Urdu Translations
- **Fateh Muhammad Jalandhari** — classic Urdu translation (public domain)
- **Balagh-ul-Quran (بلاغ القرآن)** — Urdu translation by Al-Kauthar
- **Junagarhi** Urdu translation
- Switch between translations instantly

### 📚 Tafaseer (Commentaries)
- **Tafsir Al-Kauthar (Balagh-ul-Quran)** — the app's own Al-Kauthar tafaseer
- **Bayan ul Quran** by Dr. Israr Ahmed
- Multi-tab tafsir viewer — compare multiple tafaseer for the same ayah
- Surah introductions (تعارف) with detailed background context

### 📗 Dictionary — قاموس القرآن لغات
- ~44,000+ Arabic words with Urdu meanings
- Compiled over **15 years** by **Mufti Sheikh Sajjad Hussain**
- Real-time search with diacritics-insensitive matching
- Browse mode with infinite scroll
- Word-by-word lookup: click any word in any ayah for instant dictionary meaning
- Right-click context menu integration

### 📘 Books by Mufti Sheikh Sajjad Hussain
- **مضامین القرآن (Mazameen ul Quran)** — Thematic index of Quranic topics with 3-level hierarchical tree
- **قرآنی دستور حیات ۳ (Dastoor e Hayat)** — 9 chapters of Quranic life guidance
- Accordion navigation with full-text search

[مفتی شیخ سجاد حسین کا پروفائل](https://www.facebook.com/profile.php?id=100002188643701)

### 🔍 Powerful Search
- Unified search across: Quran Arabic text, Urdu translations, Dictionary, Mazameen, and Dastoor Hayat
- Full-text search via SQLite FTS5
- Diacritics-insensitive Arabic search (auto-strips harakaat)
- Results with highlighted matches, batch selection, export to diary/clipboard

### 🎧 Audio Recitation
- Per-ayah recitation playback
- Reciters: **Abdul Basit** (Mujawwad & Murattal)
- Audio from EveryAyah.com with offline caching
- Word-by-word audio (77,000+ word audio files)
- Auto-advance to next ayah + reader sync

### 🔖 Bookmarks & Diary
- Ayah bookmarks with personal notes, surah bookmarks
- Full diary/notes system — create color-coded notes, attach multiple ayahs, add text blocks, inline editing

### 📤 Export
- Export surahs & diary notes to **PDF**, **DOCX** (Word), or **TXT**
- Include/exclude Arabic text and Urdu translation
- Copy to clipboard with formatting, print support

### 🎨 Customization
- Night mode for low-light reading
- 3 Themes: Sepia (سپیہ), Paper (صاف), Slate (سلیٹ)
- 5 Arabic fonts + 3 Urdu fonts
- Adjustable font size (8–72pt) independently for Arabic and Urdu

### 🌐 Fully Offline
- All text, fonts, and resources bundled — no internet required after installation
- Audio streaming optional with offline caching

---

## Download

| File | Platform |
|---|---|
| `Qurran-0.1.0-Windows-Setup.exe` | Windows 10/11 (64-bit) |

👉 **[Download Latest Release](https://github.com/mtaha686/Quran-desktop-offline/releases)**

---

## Installation

1. Download `Qurran-0.1.0-Windows-Setup.exe`
2. Run the installer and follow the prompts
3. Launch **Qurran** from the Start Menu or Desktop shortcut

> Requires **Windows 10 or later** (64-bit)
> Linux and macOS builds coming soon.

---

## System Requirements

- Windows 10 or later (64-bit)
- 150 MB storage

---

## Data Sources

| Data | Source |
|---|---|
| Arabic Text (IndoPak) | [Quran.com API](https://quran.com) |
| Urdu Translation (Jalandhari) | [Tanzil.net](https://tanzil.net) — public domain |
| Urdu Translation (Junagarhi) | Quran.com API (ID 54) |
| Urdu Translation (Balagh-ul-Quran) | Al-Kauthar |
| Tafsir Bayan ul Quran | Dr. Israr Ahmed |
| Tafsir Al-Kauthar | Al-Kauthar |
| Dictionary (قاموس القرآن لغات) | **Mufti Sheikh Sajjad Hussain** — 15 years of compilation |
| Mazameen & Dastoor Hayat | Written by **Mufti Sheikh Sajjad Hussain** |
| Audio Recitations | [EveryAyah.com](https://everyayah.com) |
| Word Audio | [Quran.com CDN](https://audio.qurancdn.com) |

---

## Reporting Issues

Found a bug or have a suggestion? Please report it here:

**https://github.com/mtaha686/Quran-desktop-offline/issues**

When reporting, include your Windows version and a description of the problem (screenshots appreciated).

---

## Credits

- **Mufti Sheikh Sajjad Hussain** ([Facebook](https://www.facebook.com/profile.php?id=100002188643701)) — قاموس القرآن لغات, مضامین القرآن, قرآنی دستور حیات (15 years of dedicated work)
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
