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
- **Global Hotkey (`Alt + G`)**: Conflict-free shortcut designed to work inside Word, Excel, Outlook, and text editors.
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

## 🕹️ How It Works

ClearTone runs quietly in your Windows system tray without getting in your way:

1. **Highlight Text**: Select any text in Word, Outlook, Excel, OneNote, Notepad, Slack, or your web browser.
2. **Trigger the Assistant**:
   - **Hotkey**: Press `Alt + G` to immediately open the review card.
   - **Floating Badge**: Click the small green badge that appears beside your highlighted text.
3. **Choose Your Tone**:
   - *Spelling & Grammar*: Fixes errors while keeping your exact vocabulary.
   - *Plain English*: Renders text into clear, Grade 6–8 readability.
   - *Professional*: Polishes sentences for executive and formal communication.
   - *Casual & Friendly*: Great for chat, messaging, and informal emails.
   - *Concise*: Strips unnecessary filler and redundant words.
4. **Apply Changes**: Click **Apply & Replace** to update your document automatically, or copy the refined text to your clipboard.

---

## Step-by-Step Initial Setup Guide

Setting up ClearTone takes less than 2 minutes and requires zero payment details.

### Step 1: Download ClearTone
- Go to the [Releases](https://github.com/roddan-hue/cleartone-releases/releases/latest) tab.
- Download `ClearTone.exe`.
- Move the file to any folder you prefer (e.g., `C:\Tools\ClearTone` or your `Desktop`).

### Step 2: Get a Free Groq API Key
ClearTone uses Groq's high-speed inference engine under a Bring-Your-Own-Key (BYOK) model:
1. Visit [console.groq.com](https://console.groq.com/keys) and sign up/log in (Google, GitHub, or email).
2. Click **Create API Key**.
3. Name your key (e.g., `ClearTone-Desktop`) and copy the generated key string (starts with `gsk_`).

> *Note: Groq provides a generous free tier with fast response times and zero upfront billing required.*

### Step 3: First Launch & Configuration
1. Double-click `ClearTone.exe` to run it.
2. A setup window titled **ClearTone - API Configuration** will appear on your screen.
3. Paste your Groq API key (`gsk_...`) into the field and click **Save & Continue**.
4. ClearTone will initialize and sit quietly in your Windows System Tray (near your clock).

### Step 4: Verify It's Working
- Open Notepad or Microsoft Word and type a sentence with a typo (e.g., *“Their is many problem with this report.”*).
- Highlight the sentence and press **`Alt + G`**.
- The ClearTone card will pop up with the corrected text in under a second. Click **Apply & Replace** to see it update live.

---

## Security & Data Privacy

ClearTone is built around zero-retention principles:
1. **Direct Communication**: Text requests go directly from your local machine to the official Groq API using TLS encryption.
2. **No Data Collection**: There are no telemetries, analytics, or secondary databases capturing your text.
3. **Local Footprint**: Config files and logs stay strictly inside your local Windows AppData directory.

---

## Feedback & Support

Found an issue or have a feature request? Please submit a ticket on our [GitHub Issues](https://github.com/roddan-hue/cleartone-releases/issues) page.
