# meteor-browser

# about / install / requirements

A privacy-first desktop web browser built with **Electron + Chromium**. It combines normal web browsing with privacy controls, private tabs, a clean space-themed interface, and optional AI features.

## ✨ Features

* 🌐 Real Chromium web browsing
* 🔎 Search + URL bar
* 🗂️ Multiple tabs
* 🕵️ Private browsing
* 🔒 Privacy Shield
* 🚫 Tracker blocking
* 🍪 Cookie controls
* 🛡️ HTTPS protection
* 🔐 Site permissions
* 📥 Download manager
* ⭐ Bookmarks
* 🕘 History
* 🔍 Find in page
* 🔎 Page zoom
* 🖥️ Fullscreen
* 🌠 Animated meteor background
* 🎨 Dark, light, and OLED themes
* 🤖 Optional ChatGPT and Grok integration
* ⚙️ Customizable settings

## 💻 Requirements

Before installing, make sure you have:

* **Windows 10/11** recommended
* **Node.js LTS**
* **npm** (included with Node.js)
* Internet connection for the initial dependency installation

You do **not** need Visual Studio Code or another programming editor just to run the browser.

## 📦 Installation

### 1. Install Node.js

Download **Node.js LTS** from the official website:

https://nodejs.org/

Install it using the default options.

### 2. Download the Browser

Download this repository from GitHub using **Code → Download ZIP**, then extract it.

Or clone it with:

```bash
git clone <repository-url>
cd PrivacyBrowser
```

### 3. Install Dependencies

Open Command Prompt or PowerShell inside the project folder and run:

```bash
npm install
```

This installs Electron and the other required packages.

### 4. Start the Browser

Run:

```bash
npm start
```

The browser should open in its own desktop window.

## 🪟 Windows Launcher

If the repository includes a Windows launcher, you can also double-click the provided `.bat` launcher.

The launcher can install the required dependencies and start the browser automatically.

## 🤖 AI Features

AI features are **optional**.

The browser can be used normally without ChatGPT or Grok.

If you enable AI features, you may need API credentials depending on the implementation.

**Never commit API keys to GitHub.**

Do not put API keys directly inside the source code.

## 🔐 Privacy

Privacy Browser is designed to reduce unnecessary tracking and give users more control over their browsing data.

Privacy features include:

* Tracker blocking
* Third-party cookie controls
* HTTPS upgrades
* WebRTC controls
* Permission controls
* Private browsing sessions
* Site storage controls
* Local browser data management

Privacy Browser does **not** claim to provide perfect anonymity. Websites can still receive information that you intentionally provide, especially when you sign into an account.

## 🛠️ Development

To work on the project:

```bash
npm install
npm start
```

Edit the source files, then restart the application to test changes.

## 📁 Project Structure

```text
PrivacyBrowser/
├── app/
│   ├── main/
│   ├── ui/
│   ├── privacy/
│   ├── security/
│   └── ai/
│
├── assets/
├── config/
├── launch/
├── scripts/
├── package.json
└── README.md
```

## ⚠️ Platform Notes

Windows is the primary target.

Some features may behave differently depending on the operating system, Chromium, individual websites, DRM support, or available system APIs.

YouTube, Twitch, and other modern websites are accessed through Chromium and may have their own restrictions.

## 📄 License

See the included `LICENSE` file for licensing information.


