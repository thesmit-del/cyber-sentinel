<h1 align="center"><b>Cyber Sentinel</b></h1>

## 📖 Table of Contents

-   [� Table of Contents](#-table-of-contents)
-   [🚀 Introduction](#-introduction)
-   [✨ Features](#-features)
-   [🛡️ Why Cyber Sentinel?](#️-why-cyber-sentinel)
-   [🛠 Technology Stack](#-technology-stack)
-   [⚙️ Installation](#️-installation)
    -   [1. Clone the Repo](#1-clone-the-repo)
    -   [2. Python/Flask API (localhost:5000)](#2-pythonflask-api-localhost5000)
    -   [3. Website Frontend (localhost:3000)](#3-website-frontend-localhost3000)
    -   [4. Browser Extension](#4-browser-extension)
-   [▶️ Running the Demo](#️-running-the-demo)
-   [📸 Screenshots \& 🎥 Video](#-screenshots---video)
-   [🤝 Contributing](#-contributing)
-   [🤝 Collaborators](#-collaborators)
-   [📄 License](#-license)

---

## 🚀 Introduction

**Cyber Sentinel** is a dual-component security tool that protects you from dangerous links.

1. **Browser Extension** – With just one click, it scans every clickable link inside your email — even hidden or suspicious ones — and tells you if they are safe or risky.
2. **Web Dashboard** – You can also use our companion website to scan other links if you need to.

Both components communicate with a Python/Flask backend (VirusTotal-powered) to deliver near real-time risk metrics.

---

## ✨ Features

-   **Scan all links** in an email automatically
-   Labels each link clearly as **Safe** or **Risky** with easy-to-understand icons
-   Shows more details on why a link is risky if you hover
-   Keeps your email content private — only the links are scanned
-   **SSL Certificate** validation
-   Threat Intelligence summary
-   Sleek, responsive UI

---

## 🛡️ Why Cyber Sentinel?

-   Saves you time by scanning links in one go
-   Finds hidden or tricky links you might not see
-   Helps you feel safer by showing why a link is dangerous
-   Easy to use, even if you are not technical
-   Keeps you in control of your security

---

## 🛠 Technology Stack

| Component         | Language / Framework                         |
| ----------------- | -------------------------------------------- |
| **API Server**    | Python 3.x, Flask, requests                  |
| **Frontend UI**   | Node.js, Express, EJS, CSS                   |
| **Extension**     | HTML, CSS, JavaScript, Chrome Extensions API |
| **Threat Data**   | VirusTotal API                               |
| **Fonts & Icons** | Google Fonts, custom SVG                     |

---

## ⚙️ Installation

### 1. Clone the Repo

```bash
git clone https://github.com/thesmit-del/cyber-sentinel.git
cd cyber-sentinel
```

### 2. Python/Flask API (localhost:5000)

get API key from VirusTotal and set VT_API_KEY in .env

```bash
pip install # [required libraries]
python main.py
# → http://localhost:5000
```

### 3. Website Frontend (localhost:3000)

```bash
cd ../website
npm install
node index.js
# → http://localhost:3000
```

### 4. Browser Extension

1. Open Chrome → `chrome://extensions`
2. Enable **Developer mode**
3. Click **“Load unpacked”** and select the project folder
4. Your extension icon should appear in the toolbar

---

## ▶️ Running the Demo

1. **Start** the Flask API (`localhost:5000`).
2. **Launch** the website (`localhost:3000`).
3. Open an email and then click the extension.
4. **View** threat results in the web dashboard or popup UI.

---

## 📸 Screenshots & 🎥 Video

**Images of the extension:**

<p >
    <img src="media/extension.png" width="600"/>
    <img src="media/normal_extension.png" width="193"/>
</p>
<p>
  <img src="media/safe_scan.png" width="600" align="middle" alt="Safe scan"/>
  <img src="media/safe_card.png" width="220" align="middle" alt="Safe card"/>
</p>

<p >
    <img src="media/risky_scan.png" width="600"/>
    <img src="media/risky_card.png" width="207"/>
</p>

**Demo of the extension;**

<p>
  <img src="media/ext-animation.gif" width="1000"/>
</p>

**Images of the website:**

<p >
  <img src="media/website_homepage.png" width="600"/>
</p>

<p >
    <img src="media/website_results.png" width="500"/>
    <img src="media/website_card.png" width="250"/>
</p>

**Demo of the website;**

<p>
  <img src="media/website_animation.gif" width="1000"/>
</p>

---

## 🤝 Contributing

This project is **under active development**. We welcome:

-   Bug reports & feature requests (via GitHub Issues)
-   Pull requests – please fork & branch your feature first
-   UI/UX suggestions

---

## 🤝 Collaborators

-   Aryan Vekariya (GitHub: [@Aryan0826] (https://github.com/Aryan0826))
-   Smit Delwadia (GitHub: [@thesmit-del] (https://github.com/thesmit-del))

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---
