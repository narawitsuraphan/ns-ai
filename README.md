<p align="center">
  <img src="https://raw.githubusercontent.com/narawitsuraphan/ns-ai/main/assets/icon.png" alt="NS Deck" width="110">
</p>

<h1 align="center">NS Deck</h1>

<p align="center">
  <b>Multiple terminals in a single window, built for Windows 11</b><br>
  Run cmd, PowerShell, WSL and Git Bash side by side, and launch Claude Code or Codex in one click
</p>

<p align="center">
  <a href="https://github.com/narawitsuraphan/ns-ai/releases/latest"><img src="https://img.shields.io/badge/download-v1.0.2-2ea44f?style=for-the-badge&logo=windows&logoColor=white" alt="Download"></a>
  <img src="https://img.shields.io/badge/platform-Windows%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows 11">
  <img src="https://img.shields.io/badge/license-Free-blue?style=for-the-badge" alt="Free">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/narawitsuraphan/ns-ai/main/assets/screenshot.png" alt="NS Deck application screenshot" width="900">
</p>

---

## Download

### [**Download NS Deck v1.0.2 installer**](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/NS-Deck-Setup-1.0.2.exe)

Click the link above to download. No account and no sign-in required.

| File | Purpose |
| --- | --- |
| [NS-Deck-Setup-1.0.2.exe](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/NS-Deck-Setup-1.0.2.exe) | Installer for Windows 11 |
| [latest.yml](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/latest.yml) | Version manifest used by the in-app updater |

> Browse every file on the [Releases page](https://github.com/narawitsuraphan/ns-ai/releases/latest).

---

## Installation

1. Click the download link above and wait for the `.exe` file to finish downloading.
2. Double-click the downloaded file.
3. If Windows shows the **"Windows protected your PC"** screen, click **More info** and then **Run anyway**.
   (The installer is not digitally signed yet, so this warning is expected.)
4. When installation finishes, launch the app from the **Desktop** or **Start Menu** shortcut.

---

## Features

- **Multiple terminals** - open several sessions at once in a single window and switch between grid layouts.
- **Several shells at once** - use PowerShell, Command Prompt, WSL and Git Bash together.
- **Project folders** - pick project folders, open one project or many, and every session starts in the correct directory.
- **Launch Claude Code and Codex** - start them with a single click, each with its own icon.
- **Automatic agent detection** - start an agent by hand in the terminal and the app recognises it, updating the panel name and icon.
- **Copy and paste** - paste multi-line text, with a full right-click menu.
- **Dark theme** - enabled by default and easy on the eyes, with a light theme available.
- **In-app updates** - check for, download and install new versions from inside the app without losing your data.
- **Five pages** - Terminals, Projects, Dashboard, Settings and Developer.
- **Works offline** - all icons and libraries ship with the app, so no internet connection is needed.

---

## Requirements

- Windows 11 (Windows 10 21H2 or newer also works).
- Claude Code and Codex: if they are already installed the launch buttons work right away, otherwise the app shows `not found`.
- WSL and Git Bash are optional.

---

## Frequently asked questions

**Will I lose my data when I update?**

No. Your projects, preferences, theme and layouts are stored in your Windows user profile
(`%APPDATA%\NS Deck\`), separate from the folder the application is installed in, so everything is kept across updates.
If you installed an earlier version under its previous name, your settings are carried over automatically the first time you open the new version.

**Why does Windows warn me during installation?**

Because the installer does not have a paid digital certificate yet. It does not mean the application is harmful.
Click **More info** and then **Run anyway**.

**Codex shows "start the Windows daemon from a non-elevated terminal"**

The app already handles this. Open **Settings > Agents > Fix Codex for plain terminals** and click **Fix now**.
The `codex` command then works normally everywhere, including a Command Prompt you open yourself.

**The terminal is black and white with no colour**

This is already fixed in the app. It configures colour for its own terminals only and leaves the rest of the system untouched.

---

## Privacy

The application runs entirely on your machine and sends no data anywhere.
This repository is used **only to distribute the application**. It contains no source code.

---

## Author

**Narawit Suraphan**

- GitHub: [@narawitsuraphan](https://github.com/narawitsuraphan)

<p align="center"><sub>Built for developers on Windows</sub></p>
