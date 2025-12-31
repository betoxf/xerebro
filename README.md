# Xerebro

**Your AI-powered Mac companion, controlled via Telegram.**

Xerebro is a macOS menu bar app that lets you control your entire Mac remotely through Telegram messages. Powered by Claude AI, it can see your screen, click, type, run commands, and complete complex tasks autonomously.

---

## What is Xerebro?

Xerebro acts as your personal AI assistant that lives in your Mac's menu bar. Send it a message on Telegram, and it will:

- **See your screen** - Takes screenshots and understands what's displayed
- **Control your mouse** - Click anywhere on screen with precision grid-based targeting
- **Type text** - Enter text, fill forms, write documents
- **Run commands** - Execute shell commands and scripts
- **Open apps** - Launch any application
- **Complete tasks** - Chain actions together to accomplish complex goals

All of this happens while you're away from your computer. Check on your Mac, start downloads, manage files, or have Claude work on coding tasks - all from your phone.

---

## How It Works

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  Telegram   │────▶│   Xerebro   │────▶│  Claude AI  │
│  (You)      │◀────│   (Mac)     │◀────│  (Anthropic)│
└─────────────┘     └─────────────┘     └─────────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │  Your Mac   │
                    │  - Screen   │
                    │  - Mouse    │
                    │  - Keyboard │
                    │  - Terminal │
                    └─────────────┘
```

1. **You send a message** via Telegram to your personal bot
2. **Xerebro receives it** on your Mac (runs as a menu bar app)
3. **Claude AI processes** your request and decides what actions to take
4. **Actions execute** on your Mac (screenshots, clicks, typing, commands)
5. **Results sent back** to you on Telegram

---

## Features

### Remote Computer Control
- **Grid-based clicking** - Precise mouse control using an overlay grid system
- **Keyboard input** - Type text and keyboard shortcuts
- **App launching** - Open any application via Spotlight
- **Shell commands** - Run terminal commands and get output

### AI-Powered Understanding
- **Screen comprehension** - Claude sees and understands your screen
- **Context awareness** - Knows what apps are running, what's visible
- **Task completion** - Breaks down complex requests into actions
- **Error recovery** - Handles unexpected situations intelligently

### Security & Privacy
- **Your bot, your access** - Only your Telegram ID can control it
- **Local processing** - Runs entirely on your Mac
- **Encrypted credentials** - API keys stored securely in local encrypted storage
- **No cloud storage** - Screenshots and data stay on your machine

### Menu Bar App
- **Lightweight** - Minimal resource usage
- **Always ready** - Starts automatically with your Mac (optional)
- **Status indicator** - See if the bot is running at a glance
- **Easy setup** - 3-step configuration wizard

---

## Capabilities

| Category | What Xerebro Can Do |
|----------|---------------------|
| **Screen** | Take screenshots, read text, identify UI elements |
| **Mouse** | Click, double-click, drag, scroll anywhere on screen |
| **Keyboard** | Type text, press keys, use shortcuts (Cmd+C, etc.) |
| **Apps** | Open applications, switch between windows |
| **Terminal** | Run shell commands, execute scripts, read output |
| **Files** | Navigate Finder, open files, manage folders |
| **Status** | Check running apps, active windows, system state |

---

## Example Use Cases

**"Take a screenshot and send it to me"**
> Xerebro captures your screen and sends it via Telegram

**"Open Safari and go to github.com"**
> Opens Safari, clicks address bar, types URL, presses Enter

**"Check if my download finished"**
> Takes screenshot of Downloads folder, reports status

**"Run the tests in my project"**
> Opens Terminal, navigates to project, runs test command, reports results

**"Write 'Hello World' in Notes"**
> Opens Notes app, creates new note, types the text

---

## Requirements

- **macOS 13.0+** (Ventura or later)
- **Apple Silicon or Intel Mac**
- **Telegram account**
- **Anthropic API key** (for Claude AI)

---

## Setup

### 1. Create a Telegram Bot (30 seconds)
1. Open Telegram and search for `@BotFather`
2. Send `/newbot` and follow the prompts
3. Copy the bot token you receive

### 2. Get Your Telegram ID
1. Search for `@userinfobot` on Telegram
2. Send any message
3. Copy your numeric user ID

### 3. Get an Anthropic API Key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create an API key in Settings
3. Copy the key (starts with `sk-ant-`)

### 4. Install Xerebro
1. Download the latest DMG from [Releases](../../releases)
2. Drag Xerebro to Applications
3. Open Xerebro and enter your credentials
4. Grant accessibility permissions when prompted

### 5. Start Using
1. Open Telegram and message your bot
2. Xerebro will respond and can now control your Mac!

---

## Privacy & Security

Xerebro takes your privacy seriously:

- **No data collection** - We don't collect any usage data
- **Local only** - Everything runs on your Mac
- **Your API keys** - Stored locally in AES-encrypted file
- **Your bot** - Only your Telegram ID can send commands
- **Open communication** - You see exactly what Claude does

---

## FAQ

**Is this safe?**
> Yes. Only your Telegram account can control the bot. Your credentials are encrypted locally. The app is signed and notarized by Apple.

**Does it work when my Mac is asleep?**
> No, your Mac needs to be awake. You can enable "Prevent sleep" in Energy settings.

**Can multiple people use it?**
> No, it's designed for single-user access via your Telegram ID for security.

**What's the difference between Xerebro and Mini-Xerebro?**
> Xerebro uses Claude Opus (more capable, higher cost). Mini-Xerebro uses Claude Haiku (faster, cheaper). Switch anytime from the menu bar.

**Does it work over cellular/away from home?**
> Yes! As long as your Mac has internet, you can control it from anywhere.

---

## Screenshots

*Coming soon*

---

## Download

Get the latest version from the [Releases](../../releases) page.

---

## License

Xerebro is proprietary software. All rights reserved.

---

## Support

For issues or questions, please open an issue on this repository.

---

**Built with Claude AI by Anthropic**
