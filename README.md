<p align="center">
  <img src="https://raw.githubusercontent.com/narawitsuraphan/ns-ai/main/assets/icon.png" alt="NS Deck" width="110">
</p>

<h1 align="center">NS Deck</h1>

<p align="center">
  <b>Code, terminals and a configurable AI coding agent in one workspace</b><br>
  Edit project files, organise shells, and connect the coding agent you choose
</p>

<p align="center">
  <a href="https://github.com/narawitsuraphan/ns-ai/releases/latest"><img src="https://img.shields.io/badge/download-v1.0.4-2ea44f?style=for-the-badge" alt="Download"></a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-0078D4?style=for-the-badge" alt="Windows and Linux">
  <img src="https://img.shields.io/badge/license-Free-blue?style=for-the-badge" alt="Free">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/narawitsuraphan/ns-ai/main/assets/screenshot.png" alt="NS Deck application screenshot" width="900">
</p>

---

## Download

### [**Download NS Deck for Windows**](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/NS-Deck-Setup-1.0.4.exe)

No account or sign-in is required. Linux users can download the AppImage below.

| File | Platform | Purpose |
| --- | --- | --- |
| [NS-Deck-Setup-1.0.4.exe](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/NS-Deck-Setup-1.0.4.exe) | Windows 10/11 | Windows installer |
| [NS-Deck-1.0.4.AppImage](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/NS-Deck-1.0.4.AppImage) | Linux x64 | Portable Linux app |
| [latest.yml](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/latest.yml) | Windows | In-app update manifest |
| [latest-linux.yml](https://github.com/narawitsuraphan/ns-ai/releases/latest/download/latest-linux.yml) | Linux | In-app update manifest |

> Browse every file on the [Releases page](https://github.com/narawitsuraphan/ns-ai/releases/latest).

---

## Windows installation

1. Click the download link above and wait for the `.exe` file to finish downloading.
2. Double-click the downloaded file.
3. If Windows shows the **"Windows protected your PC"** screen, click **More info** and then **Run anyway**.
   (The installer is not digitally signed yet, so this warning is expected.)
4. When installation finishes, launch the app from the **Desktop** or **Start Menu** shortcut.

---

## Features

- **Multiple terminals** - open several sessions at once in a single window and switch between grid layouts.
- **Several shells at once** - use PowerShell, Command Prompt, WSL and Git Bash on Windows, or Bash, Zsh, Fish and PowerShell 7 on Linux.
- **Project folders** - pick project folders, open one project or many, and every session starts in the correct directory.
- **Project IDE** - browse and edit text or source files in any language, open multiple tabs, search and replace across a project, review Git changes, and use language diagnostics where available. Monaco provides language modes for supported formats; other files remain editable as plain text.
- **Run files and use a built-in terminal** - get suggested commands for common runtimes, edit the command, and use Windows PowerShell in the IDE on Windows. Running code requires its runtime or compiler to be installed.
- **Configurable AI coding agent** - connect OpenRouter, Ollama or a custom OpenAI-compatible endpoint, select a model, and manage reusable Skills. Review proposed file changes and approve writes or commands before they run.
- **Launch Claude Code and Codex** - start them with a single click, each with its own icon.
- **Automatic agent detection** - start an agent by hand in the terminal and the app recognises it, updating the panel name and icon.
- **Copy and paste** - paste multi-line text, with a full right-click menu.
- **Dark theme** - enabled by default and easy on the eyes, with a light theme available.
- **In-app updates** - check for, download and install new versions from inside the app without losing your data.
- **Six pages** - Terminals, Projects, IDE, Dashboard, Settings and Developer.
- **Offline editor** - editor libraries and interface assets ship with the app. Hosted AI providers need a network connection; a local Ollama endpoint can keep AI requests on your machine.

---

## Requirements

- Windows 10 21H2 or newer, or a Linux x64 desktop with AppImage support.
- Claude Code and Codex: if they are already installed the launch buttons work right away, otherwise the app shows `not found`.
- To run code, install the matching language runtime or compiler. AI provider credentials and a reachable endpoint are needed to use the coding agent.
- Linux distributions without FUSE 2 compatibility may need the matching FUSE package from their repositories.
- WSL and Git Bash are optional on Windows.

## Linux installation

1. Download `NS-Deck-1.0.4.AppImage` from the release files above.
2. Mark the file executable in your file manager, or run `chmod +x NS-Deck-1.0.4.AppImage` in a terminal.
3. Double-click the AppImage, or launch it with `./NS-Deck-1.0.4.AppImage`.
4. If the desktop reports missing FUSE support, install the FUSE 2 compatibility package for your distribution.

---

## Frequently asked questions

**Will I lose my data when I update?**

No. Your projects, preferences, theme and layouts are stored in your per-user application data folder, separate from the app installation, so they are kept across updates on Windows and Linux.
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

The application runs on your machine and contacts this repository to check for updates. If you use the built-in AI coding agent, prompts and project context can be sent to the provider endpoint you configure. A local Ollama endpoint can keep AI processing on your machine; hosted providers have their own data practices.
This repository is used **only to distribute the application**. It contains no source code.

---

## Author

**Narawit Suraphan**

- GitHub: [@narawitsuraphan](https://github.com/narawitsuraphan)

<p align="center"><sub>Built for developers on Windows and Linux</sub></p>
