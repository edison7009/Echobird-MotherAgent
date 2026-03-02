<p align="center">
  <img src="./icon.png" alt="Echobird" width="120" />
</p>

<h1 align="center">Echobird</h1>

<p align="center">
  The Nexus for <strong>Models</strong>, <strong>Agents</strong> &amp; <strong>Vibe Coding</strong>.<br/>
  <sub>One hub to manage AI models, coding tools, and intelligent agents — built with Tauri + Rust.</sub>
</p>

<p align="center">
  <a href="https://github.com/edison7009/Echobird-MotherAgent/releases">
    <img src="https://img.shields.io/github/v/release/edison7009/Echobird-MotherAgent?style=flat-square&color=00FF9D" alt="Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/built%20with-Tauri%20%2B%20Rust-orange?style=flat-square" alt="Tauri + Rust" />
</p>

<p align="center">
  <b>English</b> ·
  <a href="./README.zh-CN.md">简体中文</a> ·
  <a href="./README.zh-TW.md">繁體中文</a> ·
  <a href="./README.ja.md">日本語</a> ·
  <a href="./README.ko.md">한국어</a>
</p>

---

## 🤖 MotherAgent — The Star Feature

**MotherAgent** is Echobird's built-in autonomous AI agent. Unlike simple chat interfaces, MotherAgent can:

- 🧠 **Think and plan** — breaks down complex tasks into actionable steps
- 🔧 **Use tools** — executes shell commands, reads files, browses the web
- 🔄 **Self-correct** — reviews its own output and retries on failure
- 💾 **Persistent memory** — conversations survive app restarts
- ⚡ **Work with any LLM** — connect your own OpenAI, Anthropic, or local model

> MotherAgent turns any LLM into a capable, autonomous coding partner.

---

## ✨ What is Echobird?

Echobird is a desktop application that gives you a **unified, visual control panel** for all your AI coding tools. No more editing config files — switch models with one click.

### Pain Points

- 😫 Switching models in tools like Claude Code, Cline, or Roo Code requires manual config edits
- 🔄 Every tool has its own model configuration format
- 🧩 No convenient way to manage skills and extensions

### Solution

Echobird is the **central control panel** for all your AI coding tools:

- 🎯 **One-click model switching** — visually switch AI models for any supported tool
- 🔀 **Dual protocol** — OpenAI & Anthropic API support, change anytime
- 🚇 **Smart tunnel proxy** — access restricted APIs without a global VPN
- 🧩 **Skill Browser** — discover, install and manage AI skills
- 🖥️ **Local LLM Server** — run open-source models locally via llama.cpp (Qwen, DeepSeek, Llama)
- 🔌 **Remote LLM** — connect to remote LLM servers (deploy your own agents)
- 🌍 **28 Languages** — full internationalization
- 🌃 **Cyberpunk UI** — neon-green terminal aesthetic

## 🖼️ Screenshots

### Model Nexus — Manage all AI models in one place
![Model Nexus](./1.png)

### App Manager — Switch models for all coding tools in one click
![App Manager](./2.png)

### Local Server — Run open-source models via llama.cpp
![Local Server](./3.png)

### Skill Browser — Discover and install AI skills
![Skill Browser](./4.png)

## 🚀 Quick Start

### Download

Get the latest release for your platform:

| Platform | Download |
|----------|----------|
| Windows  | [Echobird-x64-setup.exe](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| macOS (Apple Silicon) | [Echobird_aarch64.dmg](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| macOS (Intel) | [Echobird_x64.dmg](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| Linux | [Echobird_amd64.AppImage](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |

### Linux Notes

```bash
chmod +x Echobird_*.AppImage
./Echobird_*.AppImage
```

> If you get a FUSE error: `sudo apt install libfuse2`

## 🔧 Supported Tools

| Tool | Status | Model Switching | Protocol |
|------|--------|-----------------|----------|
| Claude Code | ✅ Supported | ✅ | Anthropic |
| OpenClaw | ✅ Supported | ✅ | OpenAI / Anthropic |
| Cline | ✅ Supported | ✅ | OpenAI |
| Roo Code | ✅ Supported | ✅ | OpenAI |
| Continue | ✅ Supported | ✅ | OpenAI |
| OpenCode | ✅ Supported | ✅ | OpenAI |
| Codex | ✅ Supported | ✅ | OpenAI |
| Aider | ✅ Supported | ✅ | OpenAI |

## 🏗️ Tech Stack

- **Tauri 2** — cross-platform desktop framework (Rust backend)
- **Rust** — high-performance native backend
- **React + TypeScript** — UI framework
- **Vanilla CSS** — custom cyberpunk design system
- **Vite** — build tool
- **llama.cpp** — local model inference engine

## ⭐ Support

If Echobird helps you, give it a ⭐ on GitHub — it helps others discover the project!

## 📄 License

[MIT](./LICENSE)

---

<p align="center">
  Built with 💚 by the Echobird Team<br/>
  <sub>📧 <a href="mailto:hi@echobird.ai">hi@echobird.ai</a></sub>
</p>
