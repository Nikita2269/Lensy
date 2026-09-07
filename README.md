# Lensy 🔍

> **Instant on-screen OCR translator for macOS** — translate any word under your cursor with a single hotkey (`⌥T`). No copy-pasting, no window switching.

[![macOS](https://img.shields.io/badge/macOS-14.0%2B%20Sonoma-blue?logo=apple&style=flat-square)](https://www.apple.com/macos/)
[![Architecture](https://img.shields.io/badge/Architecture-Universal%20Binary%20(Apple%20Silicon%20%2B%20Intel)-orange?style=flat-square)](#)
[![Version](https://img.shields.io/badge/Release-v1.0.0--beta-emerald?style=flat-square)](https://github.com/Nikita2269/Lensy/releases/tag/v1.0.0-beta)
[![License](https://img.shields.io/badge/Price-100%25%20Free%20(BYOK)-brightgreen?style=flat-square)](#)

![Lensy Preview](media/media_EN/Screenshot%202026-08-28%20at%2015.39.55.png)

---

## ⚡️ What is Lensy?

When reading foreign documentation, technical papers, or watching videos with subtitles, encountering unfamiliar words breaks your flow. You usually have to:
1. Select the word (impossible in subtitles or images).
2. Copy it.
3. Switch to a browser / translator tab.
4. Paste and read.
5. Switch back and try to remember what you were reading.

**Lensy removes all 5 steps.** Hover your cursor over any word on screen and press **`⌥T` (Option + T)**. A floating HUD card immediately appears next to your cursor with an instant, structured linguistic breakdown.

---

## ✨ Key Features

- **Zero Text Selection Needed:** Works over Preview PDFs, video players (IINA, VLC, YouTube), terminal output, scanned docs, game windows, and complex desktop UIs.
- **100% On-Device OCR:** ScreenCaptureKit captures a small Retina crop around your cursor, and Apple Vision runs OCR locally on your Mac's Neural Engine. **Your desktop screen image never leaves your computer.**
- **Rich Linguistic Card:** Gives pronunciation, parts of speech, CEFR difficulty level (A1–C2), word frequency rating, register (formal/informal/slang), and practical collocation sentences.
- **"Ask AI" in Context:** Click "Ask AI" directly in the HUD panel to ask follow-up questions about nuance or phrasing without losing context.
- **Local History (`⌥H`):** Built-in SQLite database with fast search so you never have to re-translate recurring jargon.
- **Secure BYOK:** Bring your own free Groq API key (`gsk_...`). The key is stored in your macOS system Keychain, not in plain text.

---

## 🚀 Download & Installation

### 1. Download
Grab the latest release:  
👉 **[Download Lensy-1.0.0-beta.dmg](https://github.com/Nikita2269/Lensy/releases/download/v1.0.0-beta/Lensy-1.0.0-beta.dmg)**

### 2. Install
Open the DMG and drag **Lensy.app** into your **Applications** folder.

### 3. First Launch (Gatekeeper Notice)
Because Lensy is currently in independent beta without Apple's $99/year developer certificate, macOS Gatekeeper will show a verification prompt on first launch.
- **Right-click (or Control-click) Lensy.app → select Open → click Open in the prompt.**

### 4. Permissions & Setup
1. Grant **Accessibility** (for global hotkey listening) and **Screen Recording** (to capture the small crop under cursor).
2. Open Lensy from your menu bar → Settings.
3. Paste your free Groq API key from [console.groq.com](https://console.groq.com) (takes 1 minute to create).

---

## 🛠 System Requirements

- **macOS:** 14.0 Sonoma or later.
- **Hardware:** Universal Binary (Apple Silicon M1/M2/M3/M4 & Intel Macs).
- **Network:** Internet connection required for LLM inference via Groq.

---

## 🇷🇺 Описание на русском

**Lensy** — нативная утилита для строки меню macOS, позволяющая моментально переводить любое слово на экране по горячей клавише `⌥T` (Option + T).

- **Работает поверх всего:** Распознает текст через `Apple Vision OCR` с локального скриншота, поэтому переводит субтитры в плеерах (IINA, VLC), текст в PDF, терминале и на картинках.
- **Приватность:** Скриншоты обрабатываются на 100% локально на чипе Mac и никуда не передаются. В сеть уходит только распознанное слово.
- **Лингвистическая карточка:** Показывает транскрипцию, уровень CEFR (A1-C2), части речи, стиль и примеры в предложениях.
- **История (`⌥H`):** Локальная база SQLite для быстрого повторения слов.

---

## 💬 Community & Feedback

- Telegram канал с обновлениями и багфиксами: [t.me/lensy_app](https://t.me/lensy_app)
- Issues & bug reports: [GitHub Issues](https://github.com/Nikita2269/Lensy/issues)
