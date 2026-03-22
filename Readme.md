<div align="center">
<img src="https://raw.githubusercontent.com/ftlcollective/Cybershield_project_WTB5.0_grp45/d6b20fee8fada94ed8352381fa677538936342a9/Images/IMG_1844.png" alt="Team Cyber Shield Logo" width="220"/>

> **A behavioural cybersecurity training system that turns users into human firewalls through AI-powered scam simulation.**

[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-00FF9C?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Live-00FF9C?style=for-the-badge)]()

**[▶️ Play Live Demo](https://ftlcollective.github.io/Cybershield_project_WTB5.0_grp45)** &nbsp;|&nbsp; **[📄 Documentation](#-table-of-contents)** &nbsp;|&nbsp; **[🧠 AI Component](#-ai--behavioural-analysis-engine)** &nbsp;|&nbsp; **[🚀 Quick Start](#-quick-start)**

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Problem Statement](#-problem-statement)
- [SDG Alignment](#-sdg-alignment)
- [Game Features](#-game-features)
- [Level Design](#-level-design)
- [AI — Behavioural Analysis Engine](#-ai--behavioural-analysis-engine)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Folder Structure](#-folder-structure)
- [Screenshots](#-screenshots)
- [Team](#-team)
- [License](#-license)

---

## 🎯 About the Project

**Cyber Shield: Human Firewall Challenge** is a gamified, escape-room-style cybersecurity training game. Players must survive 5 escalating cyber threats — from phishing emails to multi-step identity theft attacks.

Every decision is tracked by an AI-powered **Behavioural Analysis Engine** that computes a personalised **Human Risk Score** and classifies the player's vulnerability pattern in real time.

> This is NOT just a game. It is a **behavioural cybersecurity training system** designed to build real, lasting cyber immunity.

---

## 🚨 Problem Statement

- 💸 Cybercrime costs Africa billions annually
- 🧠 Over **70% of cyber attacks** exploit human behaviour, not technical vulnerabilities
- 📚 Most cybersecurity training is **boring, passive, and forgettable**
- 🎯 People learn best through **realistic, high-stakes experience**

---

## 🌍 SDG Alignment

| SDG | Goal | How Cyber Shield Helps |
|-----|------|------------------------|
| **SDG 4** | Quality Education | Delivers interactive digital literacy training |
| **SDG 16** | Peace, Justice & Strong Institutions | Reduces cybercrime victimisation in communities |
| **SDG 10** | Reduced Inequalities | Free, accessible cyber training for all demographics |

---

## 🎮 Game Features

| Feature | Description |
|--------|-------------|
| ❤️ **Trust Meter** | Health system — drains on bad decisions, starts at 100 |
| ⏱️ **Countdown Timer** | Per-level pressure timer (30–55 seconds) |
| 💰 **Virtual Money** | $50,000 at stake — wrong decisions cost real amounts |
| 🧠 **Behavioural AI** | Real-time Human Risk Score + pattern classification |
| 🏆 **Leaderboard** | Score-ranked board based on trust, money & levels |
| 🏅 **Badge System** | 5 achievement badges based on performance |
| ⚡ **Instant Feedback** | Explanation after every decision with security tip |
| 🔚 **Dynamic Endings** | Cyber Master / Human Firewall / Digitally Bankrupt |

### 🏅 Badges

| Badge | Condition |
|-------|-----------|
| 🎯 Phishing Sniper | Identified the first scam correctly |
| 🛡️ Scam Survivor | Completed 3+ levels |
| 😅 Too Trusting | Fell for 2+ scams |
| 🔥 Human Firewall | Completed all levels with 70+ trust |
| 💎 Cyber Master | Perfect run — no money lost |

---

## 🗺️ Level Design

```
Level 1 — 📧 Phishing Email          (45 sec)
Level 2 — 💬 Fake WhatsApp Scam      (35 sec)
Level 3 — 🔐 Fake Login Page         (40 sec)
Level 4 — 😰 Vishing Phone Call      (30 sec)
Level 5 — 🕸️ Multi-Step Attack       (55 sec)
```

Each level presents a **realistic scenario UI** (email client, WhatsApp chat, browser login, phone call) with multiple choices that affect:
- Trust Meter ❤️
- Virtual Money 💰
- AI Risk Score 🧠

---

## 🤖 AI — Behavioural Analysis Engine

The **Behavioural Analysis Engine (BAE)** is the core AI component. It analyses player behaviour across all 5 levels.

### What it tracks:

| Signal | Weight | Description |
|--------|--------|-------------|
| Wrong decision | +20 risk | Base penalty per incorrect choice |
| Impulsive wrong answer | +10 risk | Decision made in under 4 seconds |
| Authority bias | +8 risk | Fell for an authority-based manipulation |
| Urgency bias | +8 risk | Fell for a fear/urgency-based manipulation |

### Output:

| Score Range | Archetype |
|-------------|-----------|
| 0% wrong | 🛡️ Hyper-Vigilant |
| < 30% wrong | ⚠️ Cautious but Vulnerable |
| < 60% wrong | 😟 Too Trusting |
| 60%+ wrong | 🚨 High Risk Behaviour |

---

## 💻 Tech Stack

| Technology | Usage |
|-----------|-------|
| **React 18** | Frontend UI framework |
| **React Hooks** | State, effects, callbacks |
| **Vanilla CSS-in-JS** | Inline styling + injected keyframes |
| **Google Fonts** | Inter typeface |
| **Custom BAE** | AI behavioural analysis (pure JS) |
| **SVG** | Animated circular timer ring |

---

## 🚀 Quick Start

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ftlcollective/Cybershield_project_WTB5.0_grp45.git

# 2. Navigate into the project
cd C:\Users\username\folder\cybershield 

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
```

### Deploy to Vercel

```bash
npm install -g vercel
vercel
```

---

## 📁 Folder Structure

```
Cybershield_project_WTB5.0_grp45/
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── App.js              ← All game logic, AI engine & UI
│   ├── index.js            ← React entry point
│   └── logo.png            ← Team Cyber Shield logo
│
├── Images/
│   ├── IMG_1844.png               ← Team Cyber Shield logo
│   ├── screenshot-intro.png       ← Intro / home screen
│   ├── screenshot-level1.png      ← Phishing email level
│   ├── screenshot-level2.png      ← WhatsApp scam level
│   ├── screenshot-level3.png      ← Fake login page level
│   ├── screenshot-level4.png      ← Vishing call level
│   ├── screenshot-level5.png      ← Multi-step attack level
│   ├── screenshot-feedback.png    ← Feedback screen
│   └── screenshot-endscreen.png   ← End / results screen
│
├── .gitignore
├── package.json
└── README.md
```

---

## 📸 Screenshots

| Screen | Screenshot | Description |
|--------|------------|-------------|
| 🏠 Intro | ![Intro](Images/screenshot-intro.png) | Mission briefing + agent name entry |
| 📧 Level 1 | ![Level 1](Images/screenshot-level1.png) | Phishing email simulation |
| 💬 Level 2 | ![Level 2](Images/screenshot-level2.png) | WhatsApp scam chat UI |
| 🔐 Level 3 | ![Level 3](Images/screenshot-level3.png) | Fake bank login page |
| 😰 Level 4 | ![Level 4](Images/screenshot-level4.png) | Live vishing call simulation |
| 🕸️ Level 5 | ![Level 5](Images/screenshot-level5.png) | Multi-vector recruitment scam |
| 📊 Feedback | ![Feedback](Images/screenshot-feedback.png) | AI analysis + security tip |
| 🏆 End Screen | ![End](Images/screenshot-endscreen.png) | Final score, badges & ending |

> 📸 *Add screenshots by saving images into the `/Images` folder and pushing to GitHub.*

---

## 👥 Team

**Team Cyber Shield** — Joint Effort 🤝

ToolRole🤖 Claude (Anthropic)Primary development — frontend, AI engine, UI/UX💬 ChatGPT (OpenAI)Content, ideation, scam scenarios✨ Google GeminiResearch, validation, SDG alignment🔍 Google ResearchCybercrime statistics & real-world data
Plus a Combined AI + Human Intelligence callout at the bottom.

## 🤖 AI Tools & Research Methodology

This project was built using a **combination of AI tools, combined research, and collaborative development** — each contributing a unique strength to the final product.

| Tool | Role |
|------|------|
🤖 Claude — Primary dev
💬 ChatGPT — Content & ideation
✨ Gemini — Research & validation
🔍 Google — Data & statistics 🛡️

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤖 AI Tools & Research Methodology

This project was built using a **combination of AI tools, combined research, and collaborative development** — each contributing a unique strength to the final product.

| Tool | Role |
|------|------|
| 🤖 **Claude (Anthropic)** | Primary development — frontend, game logic, Behavioural Analysis Engine, UI/UX design, documentation |
| 💬 **ChatGPT (OpenAI)** | Brainstorming scam scenarios, refining problem statements, drafting initial proposal content |
| ✨ **Google Gemini** | Cross-referencing cybersecurity statistics, validating scam patterns, SDG alignment research |
| 🔍 **Google Research** | Sourcing cybercrime statistics, real-world scam examples, and best practices in cybersecurity training |

> 🤝 **Combined AI + Human Intelligence Approach** — Multiple AI tools were used collaboratively alongside team research and human insight, ensuring the platform is accurate, realistic, and impactful.

---

## Submission Note — Version History

This project was originally developed as a React application using Node.js and the react-scripts build toolchain (npm start / npm run build), with the component logic contained in src/App.js and bootstrapped via src/index.js. This version remains intact in the repository as the original development build and reflects the full React-based architecture as designed. For final submission purposes, the application was subsequently converted into a self-contained single-file HTML document (CyberShield.html), which bundles the React 18 runtime and Babel transpiler via CDN, eliminating the requirement for a local Node.js environment. All game logic, the Behavioural Analysis Engine, UI components, level scenarios, and documentation remain functionally identical between both versions. The self-contained HTML file can be opened directly in any modern browser or accessed via the GitHub Pages deployment link, and is designated as the final submission version.

## 🙏 Acknowledgements

- Inspired by real cybercrime statistics across **Africa**
- Designed to support **UN Sustainable Development Goals 4, 10 & 16**
- Built as a capstone project for **WOMEN TECHSTERS BOOTCAMPE 5.0 BY TECH4DEV**

---

<div align="center">

**"Every person who plays Cyber Shield becomes a Human Firewall."**

⭐ Star this repo if you found it useful &nbsp;|&nbsp; 🐛 [Report a Bug](https://github.com/ftlcollective/Cybershield_project_WTB5.0_grp45/issues) &nbsp;|&nbsp; 💡 [Request a Feature](https://github.com/ftlcollective/Cybershield_project_WTB5.0_grp45/issues)

Made with 💙 by **Team Cyber Shield**

</div>
