<div align="center">


  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0FBF3E&text=GitHub%20Absolute%20Dates&fontColor=auto&fontSize=55&animation=twinkling" alt="GitHub Absolute Dates Banner" width="100%" />

  <img src="https://raw.githubusercontent.com/PacificCosmophile/GitHub-Absolute-Dates/main/icons/icon-green.png" width="128" alt="GitHub Absolute Dates Logo">

  ### 📅 Precision Timestamps for GitHub

  **Transform vague relative timestamps like *"2 hours ago"* into clear, localized, and fully customizable absolute dates.**

  <br />

  <a href="https://greasyfork.org/en/scripts/588662">
    <img src="https://img.shields.io/badge/Install%20via-GreasyFork-red?style=for-the-badge&logo=greasyfork" alt="GreasyFork">
  </a>
  <a href="https://day.js.org/">
    <img src="https://img.shields.io/badge/Powered%20by-Day.js-8534F3?style=for-the-badge&logo=javascript" alt="Day.js">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-0FBF3E?style=for-the-badge" alt="MIT License">
  </a>

  <br /><br />

  <a href="#-installation"><strong>🚀 Quick Install</strong></a> •
  <a href="#-features"><strong>✨ Features</strong></a> •
  <a href="#%EF%B8%8F-settings--keyboard-shortcuts"><strong>⚙️ Settings</strong></a> •
  <a href="#-supported-pages"><strong>🌐 Compatibility</strong></a>

</div>

---

## 📖 Overview

GitHub displays relative timestamps across repositories, issues, and pull requests—such as **"2 hours ago"**, **"last week"**, or **"3 months ago"**. Finding exact dates often requires hovering over each timestamp individually.

**GitHub Absolute Dates** automatically converts relative timestamps into human-readable, precise, and fully customizable absolute dates throughout GitHub's entire interface.

> [!NOTE]
> The script is lightweight, fast, dynamic, and runs strictly inside your browser with zero performance overhead.

---

## ✨ Features

- ⚡ **Instant Conversion** — Replaces relative timestamps across GitHub automatically.
- 🎨 **Fully Customizable** — Tailor formats using **[Day.js](https://day.js.org/docs/en/display/format)** tokens (e.g., `D MMM YYYY h:mm a`).
- 🔤 **Custom Prefixes** — Add optional words before dates (e.g., *at*, *on*, *updated*).
- ⌨️ **Keyboard Shortcuts** — Built-in panel shortcuts for fast configuration.
- 👁️ **Live Preview** — Test your date formatting in real-time before saving.
- 🔄 **Dynamic Navigation** — Works smoothly with GitHub’s dynamic page loads & AJAX scrolling via `MutationObserver`.
- 🔒 **Privacy First** — Client-side only with zero data collection or tracking.

---

## 📸 Before & After

| State | Preview | Output |
| :--- | :--- | :--- |
| **Before** | `2 hours ago` | Relative & Vague |
| **After** | <kbd>26 Jul 2026 2:15 pm</kbd> | Standard Absolute |
| **With Prefix** | <kbd>at 23 Jul 2026 10:41 am</kbd> | Custom Prefix Included |

---

## 🚀 Installation

> [!IMPORTANT]
> A userscript manager must be installed in your browser prior to installing this script.

### Step 1: Install a Userscript Manager

| Browser / Platform | Recommended Extension |
| :--- | :--- |
| **Chromium / Firefox** | [<img src="https://img.shields.io/badge/Violentmonkey-Free%20%26%20Open%20Source-blue?style=flat-square&logo=firefoxbrowser" />](https://violentmonkey.github.io/) |
| **Chrome / Edge / Opera** | [<img src="https://img.shields.io/badge/Tampermonkey-Popular-green?style=flat-square&logo=googlechrome" />](https://www.tampermonkey.net/) |
| **Firefox** | [<img src="https://img.shields.io/badge/Greasemonkey-Legacy-orange?style=flat-square&logo=firefox" />](https://www.greasespot.net/) |

> [!TIP]
> **Violentmonkey** is recommended for optimal performance and open-source transparency.

### Step 2: Install the Script

Click the button below to install directly:

[![](https://img.shields.io/badge/🚀_Install_Userscript-Click_Here-success?style=for-the-badge&logo=tampermonkey)](https://greasyfork.org/en/scripts/588662)

---

## ⚙️ Settings & Keyboard Shortcuts

Access the terminal-style configuration dialog directly on any GitHub page to personalize your setup:

- **Word before dates:** Custom prefix strings.
- **Date format:** Powered by standard Day.js syntax.
- **Alignment:** Customize alignment inside repository file lists.

### ⌨️ Shortcuts

| Action | Shortcut |
| :--- | :--- |
| **Save Settings** | <kbd>Ctrl</kbd> + <kbd>S</kbd> or <kbd>⌘</kbd> + <kbd>S</kbd> |
| **Close Dialog** | <kbd>Esc</kbd> |

---

## 📅 Common Date Formats

Modify your format string using any valid **Day.js** tokens:

| Tokens | Output Example | Note |
| :--- | :--- | :--- |
| `D MMM YYYY h:mm a` | `26 Jul 2026 2:15 pm` | Default Format |
| `YYYY/MM/DD HH:mm` | `2026/07/26 14:15` | ISO / Standard 24h |
| `DD MMMM YYYY` | `26 July 2026` | Full Month Name |
| `ddd, D MMM YYYY` | `Sun, 26 Jul 2026` | Includes Day of Week |

---

## 🌐 Supported Pages

<details>
<summary><strong>Click to expand full list of supported GitHub pages</strong></summary>

<br />

- 📁 Repositories & File Lists
- 🐛 Issues & Pull Requests
- 💬 Discussions
- 🔀 Commits & Releases
- 📜 File History & Blame
- 🔔 Notifications
- 🌐 All pages rendering `<relative-time>` elements

</details>

---

## ⚡ Performance & Compatibility

- **Minimal DOM Overhead:** Operates via standard `MutationObserver` targeting only modified timestamp tags.
- **Lightweight Footprint:** Zero external heavy library calls (bundles lightweight Day.js).
- **Theme Native:** Automatically matches GitHub's Light, Dark, and High Contrast themes.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full details.

---

<div align="center">

Crafted with ❤️ for developers who prefer precision.

</div>
