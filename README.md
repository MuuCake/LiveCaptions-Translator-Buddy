
<div align="center">

<img src="assets/readme_accent.png" alt="" width="820">

# LiveCaptions Translator Buddy

**Real-time captions, live translation, and TXT recording — with a cute anime desktop companion.**

Capture speech, translate subtitles, and save bilingual transcripts on Windows 11.

![Windows 11](https://img.shields.io/badge/Windows-11-0078D4?logo=windows11&logoColor=white)
[![Latest Release](https://img.shields.io/github/v/release/MuuCake/LiveCaptions-Translator-Buddy?label=Latest%20Release&color=70B89A)](https://github.com/MuuCake/LiveCaptions-Translator-Buddy/releases/latest)
![12 UI Languages](https://img.shields.io/badge/UI%20Languages-12-A995DB)

### Live Translation in Action

<img src="assets/gif1_readme_reencoded.gif" alt="Korean-to-English live translation with the desktop companion" width="720">

### [Download for Windows (x64)](https://github.com/MuuCake/LiveCaptions-Translator-Buddy/releases/latest)

Download the **Windows x64 ZIP**, extract all files, keep the `_internal` folder, and run `LiveCaptionV1.5.0.exe` (no Python installation required).

**繁體中文：** 下載最新的 **Windows x64 ZIP 壓縮檔**，完整解壓縮後保留 `_internal` 資料夾，再執行 `LiveCaptionV1.5.0.exe`，無須安裝 Python。

</div>

---

## Features

### Live Captions & Translation
- **Two input modes:** System Audio and Microphone, using Windows 11 Live Captions.
- **Two translation services:** Google Translate and Tencent TranSmart.
- **Incremental updates:** Translations refresh as new captions arrive.
- **Three preview modes:** Original, Translated, and Bilingual.
- **Flexible TXT export:** Save original text, translations, or both.

### TXT Recording & History
- Custom TXT filenames, save folders, and optional timestamps.
- Pause, resume, stop, and save recordings.
- Automatic backups and recovery after unexpected interruptions.
- Searchable SQLite history and a built-in TXT reader.

### Anime Desktop Companion
- **Wakaba Mutsumi** desktop pet with blinking, breathing, and sleepy animations.
- Click to interact, drag to move, and resize to **160 / 200 / 240 / 280 px**.
- Floating subtitle bubbles with original, translated, or bilingual text.
- Bubble placement: **Automatic / Left / Right**.

### Interface & Appearance
- **12 UI languages** with in-app language selection.
- Automatic Windows light/dark theme support.
- Adjustable recording, translation, and appearance settings.

---

## Screenshots & Demos

### Main UI & Translation Settings
Choose input modes, translation services, and languages.

<div align="center">
<img src="assets/GIF2_UI_Demo.gif" alt="Main interface and translation settings" width="720">
</div>

### Desktop Pet Customization
Move the pet, change its size, and switch subtitle bubbles between left and right.

<div align="center">
<img src="assets/GIF3_Customization.gif" alt="Pet movement, size, and subtitle bubble position" width="780">
</div>

### Light & Dark Mode

<div align="center">
<img src="assets/theme_comparison.png" alt="Light and dark theme comparison" width="850">
</div>

---

## Supported UI Languages

| Language | Language |
|---|---|
| English | Português (Brasil) |
| 한국어 | Bahasa Indonesia |
| 简体中文 | Deutsch |
| 繁體中文 | Türkçe |
| 日本語 | Français |
| Español | Русский |

**Note:** These are **interface languages**, not a fixed list of speech-recognition or translation languages. Speech recognition is provided by Windows Live Captions.

## Translation Notes

Google Translate and Tencent TranSmart are selectable translation services. An internet connection is required, and availability depends on your network.

> **繁體中文提醒：** 中國大陸用戶建議優先選擇 **騰訊翻譯（Tencent TranSmart）**；Google 翻譯在部分網路環境下可能無法正常使用。

## Quick Start

1. Open the extracted application and select **System Audio** or **Microphone**.
2. Choose your translation service, target language, and preview mode if needed.
3. Record captions and save a TXT file, or review previous files in **History**.

## Requirements & Notes

- **Windows 11 (64-bit)** with Windows Live Captions.
- **Internet access** for online translation.
- **No Python installation** needed for the packaged EXE.
- This release is **not code-signed**; Windows may show a security warning. Verify the download source before running it.

---

## Credits & License

Made by **[MuuCake](https://github.com/MuuCake)**. Built with Python and PySide6/Qt, using Windows Live Captions and the selected translation service.

Wakaba Mutsumi is a character from *BanG Dream! Ave Mujica*. This is an **unofficial project**, not affiliated with or endorsed by Microsoft, Google, Tencent, or the character rights holders.

Earlier published source files in this repository use the [MIT License](LICENSE). **The v1.5.0 application is released as a compiled Windows package; its application source code is not public.** Third-party libraries, characters, artwork, and trademarks remain subject to their own licenses and rights.

<div align="center">

<img src="assets/readme_accent.png" alt="" width="820">

[Download Latest Release](https://github.com/MuuCake/LiveCaptions-Translator-Buddy/releases/latest)

</div>
