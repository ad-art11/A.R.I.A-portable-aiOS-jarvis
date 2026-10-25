<p align="center">
  <img src="docs/screenshots/main.png" alt="A.R.I.A. main screen: the HUD core, the chat and the workspace window" width="100%">
</p>

<h1 align="center">A.R.I.A.</h1>
<p align="center"><b>Adaptive · Reasoning · Interface · Assistant</b><br>
A desktop AI assistant with a living core — many AI agents, offline voice, a real workspace and computer control.<br>
Runs from a USB drive on Windows, macOS and Linux.</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-v0.34-3fe0ff?style=for-the-badge" alt="Download"></a>
  <a href="docs/ARIA-User-Manual.pdf"><img src="https://img.shields.io/badge/Manual-PDF-0b1a20?style=for-the-badge" alt="User manual (PDF)"></a>
  <a href="https://ko-fi.com/aria_assistant"><img src="https://img.shields.io/badge/Ko--fi-Buy%20me%20a%20coffee-ff8a3d?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Buy me a coffee on Ko-fi"></a>
</p>

## What she does

- **Many agents, one interface** — Claude, Gemini, OpenAI, Mistral, DeepSeek, Groq, OpenRouter and more. A.R.I.A. picks the right agent for every message, or you choose.
- **Local AI built in** — download a model from inside the app and run it on your own computer: free, private, offline. No Ollama needed.
- **Voice, offline** — natural voices in about 40 languages and offline speech recognition. Say *“Aria…”* or your own wake-up phrase.
- **Real work on your computer** — with your permission, agents write files, build websites and apps, run commands, open programs, print, and click and type in programs that are already open.
- **A workspace you can watch** — Code, Blueprint, Preview, Files, a real Terminal, Activity and Sessions. Move it to any monitor.
- **Blueprint** — map an app before it is built, by hand or with AI, then build it part by part.
- **Your rules** — every kind of action is *Always*, *Ask* or *Never*; agents only reach the folders you allow.
- **Portable** — settings, keys (password-protected), voices, models and projects travel with you on the drive. Nothing stays behind.

## Screenshots

| | |
|---|---|
| <img src="docs/screenshots/terminal.png" alt="The workspace with a real terminal"> | <img src="docs/screenshots/blueprint.png" alt="Blueprint: the map of a web app"> |
| **A real terminal** — PowerShell, zsh or bash, right in the workspace | **Blueprint** — plan an app, then build it part by part |
| <img src="docs/screenshots/settings.png" alt="Settings: themes and appearance"> | <img src="docs/screenshots/support-me.png" alt="Support me: buy the author a coffee"> |
| **12 themes, 6 core styles** — and tidy, foldable settings | **Support me** — scan the QR code or open Ko-fi in your browser |

## Install on a USB drive

1. **Download** the package for your system from [Releases](../../releases/latest): `ARIA-USB-Windows.zip`, `ARIA-USB-macOS.zip` (Apple Silicon + Intel) or `ARIA-USB-Linux.zip` — or all three.
2. **Format** a fast USB 3 drive (32 GB or more) as **exFAT**, so every system can use it.
3. **Unpack** the packages straight into the **top folder** of the drive. You should see the `ARIA-data` folder right away. *(Unpack the macOS package on a Mac.)*
4. **Start** her with `Start ARIA (Windows).bat`, `Start ARIA (Mac).command` (right-click › Open the first time) or `Start ARIA (Linux).sh`.
5. **Choose a password** — it protects your API keys on the drive.
6. **Add an AI agent** in *Settings › Agents* (paste an API key) or download a local model in *Settings › Local models*.

Optional: run *Install auto-start* from the `Auto-start` folder once on your own computers, and A.R.I.A. starts by herself whenever you plug the drive in.

The same packages also run from a folder on your computer's disk. Everything is explained step by step in the **[user manual (PDF)](docs/ARIA-User-Manual.pdf)**, which is also included in every package.

**Requirements:** Windows 10/11 (64-bit), macOS 12 or later, or a 64-bit Linux desktop · 8 GB of memory (16 GB for local AI models) · an API key from an AI provider, or a local model.

> **First start:** Windows may say *“Windows protected your PC”* — click *More info › Run anyway*. On macOS, right-click the start file › *Open*. On Linux, install `libfuse2` if the app does not start.

## Support me ☕

A.R.I.A. is free. A lot of late evenings went into building her — if she saves you time and you would like to say thank you, you can **[buy me a coffee on Ko-fi](https://ko-fi.com/aria_assistant)**. Pay with Apple Pay, Google Pay, a card or PayPal. Every coffee helps me keep improving her. Thank you!

<p align="center"><a href="https://ko-fi.com/aria_assistant"><img src="https://img.shields.io/badge/Ko--fi-Buy%20me%20a%20coffee-ff8a3d?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Buy me a coffee on Ko-fi"></a></p>

## Privacy

Your messages go only to the AI provider of the agent that answers — local models keep everything on your computer. Speech recognition, the wake word and offline voices never send audio anywhere. A.R.I.A. sends no usage statistics.
