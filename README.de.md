<p align="center">
  <img src="./icon.png" alt="Echobird" width="120" />
</p>

<h1 align="center">Echobird</h1>

<p align="center">
  The Nexus for <strong>Models</strong>, <strong>Agents</strong> & <strong>Vibe Coding</strong>.<br/>
  <sub>Echobird ist eine Desktop-Anwendung, die eine</sub>
</p>

<p align="center">
  <a href="https://github.com/edison7009/Echobird-MotherAgent/releases">
    <img src="https://img.shields.io/github/v/release/edison7009/Echobird-MotherAgent?style=flat-square&color=00FF9D" alt="Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/github/license/edison7009/Echobird-MotherAgent?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="./README.md">English</a> · <a href="./README.zh-CN.md">简体中�?/a> · <a href="./README.zh-TW.md">繁體中文</a> · <a href="./README.ja.md">日本�?/a> · <a href="./README.ko.md">한국�?/a> · <a href="./README.es.md">Español</a> · <a href="./README.fr.md">Français</a> · **Deutsch** · <a href="./README.pt.md">Português</a> · <a href="./README.ru.md">Русский</a> · <a href="./README.ar.md">العربية</a>
</p>

---

## �?Was ist Echobird?

Echobird ist eine Desktop-Anwendung, die eine **visuelle, einheitliche Oberfläche** zur Verwaltung von KI-Modellen in deinen Programmier-Tools bietet. Kein Durchsuchen von Konfigurationsdateien mehr �?einfach klicken und wechseln.

### Das Problem

- 😫 Das Wechseln von KI-Modellen in Tools wie OpenClaw erfordert manuelles Bearbeiten von Konfigurationsdateien
- 🔄 Jedes Tool hat sein eigenes Modell-Konfigurationsformat
- 🧩 Keine einfache Möglichkeit, Skills und Erweiterungen über Tools hinweg zu verwalten

### Die Lösung

Echobird fungiert als **zentrale Steuerungszentrale** für alle deine KI-Programmier-Tools:

- 🎯 **Ein-Klick Modellwechsel** �?Visuell KI-Modelle für jedes unterstützte Tool wechseln
- 🔀 **Dual-Protokoll** �?OpenAI & Anthropic API-Unterstützung, jederzeit und überall Modelle wechseln
- 🚇 **Intelligenter Tunnel-Proxy** �?Zugriff auf geo-beschränkte APIs ohne vollständiges VPN; nur API-Traffic wird proxied
- 🧩 **Skill-Browser** �?KI-Skills entdecken, installieren und verwalten
- 🖥�?**Lokaler Modell-Server** �?Open-Source-Modelle (Qwen, DeepSeek, Llama) lokal über llama.cpp ausführen
- 🌍 **28 Sprachen** �?Vollständige Internationalisierung
- 🎮 **Integrierte KI-Apps** �?Interaktive KI-Spiele und Werkzeuge wie Reversi und AI Translate
- 🌃 **Cyberpunk-UI** �?Atemberaubende neongrüne Terminal-Ästhetik für futuristisches Programmieren

## 🖼�?Screenshots

### Model Nexus �?Alle KI-Modelle an einem Ort verwalten
![Model Nexus](1.png)

### App Manager �?Ein-Klick Modellwechsel für alle Coding-Tools
![App Manager](2.png)

### Local Server �?Open-Source-Modelle lokal mit llama.cpp ausführen
![Local Server](3.png)

### Skill Browser �?KI-Skills entdecken und installieren
![Skill Browser](4.png)

## 🚀 Schnellstart

### Download

Hol dir die neueste Version für deine Plattform:

| Plattform | Download |
|----------|----------|
| Windows  | [Echobird-Setup.exe](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| macOS    | [Echobird.dmg](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| Linux    | [Echobird.AppImage](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |

### Linux-Hinweise

```bash
chmod +x Echobird-*.AppImage
./Echobird-*.AppImage
```

> Bei FUSE-Fehlern: `sudo apt install libfuse2`

## 🔧 Unterstützte Tools

| Tool | Status | Modellwechsel | Protokoll |
|------|--------|----------------|----------|
| OpenClaw | �?Unterstützt | �?| OpenAI / Anthropic |
| Claude Code | �?Unterstützt | �?| Anthropic |
| Cline | �?Unterstützt | �?| OpenAI |
| Continue | �?Unterstützt | �?| OpenAI |
| OpenCode | �?Unterstützt | �?| OpenAI |
| Codex | �?Unterstützt | �?| OpenAI |
| Roo Code | �?Unterstützt | �?| OpenAI |

## 🏗�?Tech-Stack

- **Electron** �?Plattformübergreifendes Desktop-Framework
- **React + TypeScript** �?UI-Framework
- **Vanilla CSS** �?Benutzerdefiniertes Cyberpunk-Designsystem
- **Vite** �?Build-Tool
- **llama.cpp** �?Lokale Modell-Inferenz-Engine

## 🛠�?Entwicklung

```bash
npm install
npm run dev
npm run build
```

## 🤝 Mitwirken

Beiträge sind willkommen! Erstelle gerne Issues oder sende Pull Requests.

We're especially looking for help with:
- 🍎 **macOS-Tests** �?Wir haben die macOS-Builds noch nicht vollständig getestet
- 🔧 **Neue Tool-Integrationen** �?Hilf uns, mehr KI-Tools zu unterstützen
- 🌐 **Übersetzungsverbesserungen** �?Muttersprachler willkommen!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📬 Contact

- 📧 Email: [hi@echobird.ai](mailto:hi@echobird.ai)
- 🐛 Bug Reports: [GitHub Issues](https://github.com/edison7009/Echobird/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/edison7009/Echobird/discussions)

## �?Unterstützung

Wenn du Echobird nützlich findest, gib bitte einen �?auf GitHub �?das hilft anderen, das Projekt zu entdecken!

## 📄 Lizenz

[MIT](../LICENSE)

---

<p align="center">
  Mit 💚 vom Echobird Team erstellt<br/>
  <sub>📧 <a href="mailto:hi@echobird.ai">hi@echobird.ai</a></sub>
</p>
