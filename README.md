# Notch: The Sovereign AI Overlay (Alpha v0.1)

> **"The browser is dead. Long live the Interface."**

<img width="1920" height="1080" alt="transparent Notch" src="https://github.com/user-attachments/assets/36caa492-b9ff-40bf-9c27-4525fe7f6895" />

Notch is a **native, sovereign AI overlay** that lives *on top* of your Windows workflow. 

Built out of frustration with browser-based AI ("Alt-Tab fatigue") and frequent power cuts that wiped context, Notch is designed to be a persistent, "God-Mode" utility that **never forgets**.

## ⚡ Why Notch?

* **Zero-Latency Overlay:** Press `Win + Shift + Space` (configurable) to summon Notch instantly over VS Code, Unity, or any app. No context switching.
* **Sovereign Memory:** Uses a local vector-lite system (`.json`) to remember your context forever. It survives reboots and power outages.
* **God Mode:** Control your system directly.
    * *"Turn volume up"*

    * *"Launch Discord"*
    * *"Close Chrome"*
* **BYOK (Bring Your Own Key):** Plug in your own **Groq (Llama 3)**, **Gemini**, or **Anthropic** keys. No monthly subscriptions. You own the intelligence.
* **Privacy First:** Your data stays on your machine. Memory files are local JSONs you can read and edit.

## 🚀 Installation

1.  Go to the **[Releases Page](../../releases)**.
2.  Download the latest installer: `Notch_AI_Setup_v0.1.exe`.
3.  Run the installer (Windows SmartScreen might flag it because I'm an indie dev—click "Run Anyway").
4.  Launch **Notch AI** from your desktop.

## 🎮 Controls & Commands

| Action | Command / Hotkey |
| :--- | :--- |
| **Toggle Overlay** | `Win + Shift + Space` (Default) |
| **Voice Mode** | "Hey Notch" (Always listening) |
| **System Control** | "Open [App Name]", "Volume [Up/Down/Mute]", "Close [App Name]" |
| **Music** | "Play [Song Name]" (Opens YouTube automatically) |
| **Memory** | Just speak naturally. It remembers facts automatically. |

## 🛠️ Configuration (config.json)

![Downloads](https://img.shields.io/github/downloads/krishnasoni-pn3/Notch/total?style=for-the-badge&logo=github&color=blue)

Notch creates a `config.json` in your AppData folder. You can edit it manually or use voice commands to switch models.

```json
{
  "provider": "groq",
  "model_groq": "llama-3.3-70b-versatile",
  "keys": {
  
    "groq": "YOUR_KEY_HERE"
  }

}
