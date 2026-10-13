<div align="center">

# 🇦🇺 ClearTone
### Clarity right where you write.
#### Fast, Privacy-First Desktop Writing & Tone Assistant for Windows

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6.svg?logo=windows)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#)
[![Security](https://img.shields.io/badge/Security-BYOK%20%7C%20Local--Only-FFCD00.svg)](#)
[![Inference](https://img.shields.io/badge/Speed-Sub--300ms%20Groq%20LPU-009647.svg)](#)

[Download Latest Release](https://github.com/roddan-hue/cleartone-releases/releases/latest) • [Report an Issue](https://github.com/roddan-hue/cleartone-releases/issues)

</div>

---

## 💡 What is ClearTone?

**ClearTone** is a lightweight, privacy-focused Windows companion that brings instant grammar correction and tone refinement directly to your native apps—Microsoft Word, Outlook, Excel, OneNote, Slack, Teams, and web browsers.

Instead of paying recurring monthly SaaS subscriptions or dealing with heavy browser extensions that slow down your system, ClearTone runs as a clean, stand-alone Windows executable powered by your own free Groq API key.

---

## Features

- **Sub-300ms Corrections**: Ultra-low latency responses powered by Groq LPU chips (`Qwen 2.5` / `LLaMA 3.3`).
- **Discreet Floating Pill**: A non-intrusive badge appears right beside your highlighted text. Click to inspect suggestions without losing document focus.
- **Global Hotkey (`Win + Shift + G`)**: Conflict-free shortcut designed to work inside Word, Excel, Outlook, and text editors.
- **Privacy & Security First**:
  - Automatically suppresses itself in masked password boxes (`control.IsPassword`).
  - Ignores credential managers (1Password, Bitwarden, KeePass, Windows Security).
  - Built-in local regex filters block sensitive strings (API keys, JWT tokens, credit cards) before sending text.
- **Bring Your Own Key (BYOK)**:
  - 100% free to use with your own personal Groq Cloud key.
  - Keys are stored locally on your machine (`%APPDATA%\ClearTone\config.json`) and never routed through any middleman server.
- **5 Tone & Refinement Modes**:
  - **Spelling & Grammar**: Strict correction preserving your exact voice.
  - **Plain English**: Grade 6–8 readability and clarity.
  - **Professional**: Executive-ready, confident corporate tone.
  - **Casual & Friendly**: Great for team messaging and collaborative chats.
  - **Concise**: Eliminates fluff and redundant filler words.

---

## Installation & Setup

1. **Download**: Grab the latest `ClearTone.exe` from the [Releases](https://github.com/roddan-hue/cleartone-releases/releases/latest) tab.
2. **Launch**: Run `ClearTone.exe`.
3. **Connect API Key**:
   - On initial startup, a setup dialog will appear.
   - Enter your free API key from [Groq Cloud Console](https://console.groq.com/keys) (starts with `gsk_`).
4. **Start Writing**:
   - Highlight any text in Word, Outlook, browser, or editor.
   - Press **`Win + Shift + G`** or click the floating pill to refine.

---

## Security & Data Privacy

ClearTone is built around zero-retention principles:
1. **Direct Communication**: Text requests go directly from your local machine to the official Groq API using TLS encryption.
2. **No Data Collection**: There are no telemetries, analytics, or secondary databases capturing your text.
3. **Local Footprint**: Config files and logs stay strictly inside your local Windows AppData directory.

---

## Feedback & Support

Found an issue or have a feature request? Please submit a ticket on our [GitHub Issues](https://github.com/roddan-hue/cleartone-releases/issues) page.
