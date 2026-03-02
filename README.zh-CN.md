<p align="center">
  <img src="../build/icon.png" alt="Echobird" width="120" />
</p>

<h1 align="center">Echobird</h1>

<p align="center">
  The Nexus for <strong>Models</strong>, <strong>Agents</strong> & <strong>Vibe Coding</strong>.<br/>
  <sub>Echobird 是一款桌面应用，为你�?AI 编程工具提供可视化、统一的模型管理界面。无需再手动翻配置文件 —�?点一下，就能切换�?/sub>
</p>

<p align="center">
  <a href="https://github.com/edison7009/Echobird-MotherAgent/releases">
    <img src="https://img.shields.io/github/v/release/edison7009/Echobird?style=flat-square&color=00FF9D" alt="Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/github/license/edison7009/Echobird?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="../README.md">English</a> · **简体中�?* · <a href="./README.zh-TW.md">繁體中文</a> · <a href="./README.ja.md">日本�?/a> · <a href="./README.ko.md">한국�?/a>
</p>

---

## �?Echobird 是什么？

Echobird 是一款桌面应用，为你�?AI 编程工具提供**可视化、统一的模型管理界�?*。无需再手动翻配置文件 —�?点一下，就能切换�?
### 痛点

- 😫 �?OpenClaw 等工具中切换模型需要手动编辑配置文�?- 🔄 每个工具都有自己的模型配置格�?- 🧩 没有方便的方式管理技能和扩展

### 解决方案

Echobird 是你所�?AI 编程工具�?*中央控制面板**�?
- 🎯 **一键切换模�?* �?可视化切换任何支持工具的 AI 模型
- 🔀 **双协议支�?* �?OpenAI & Anthropic API 支持，随时随地切换模�?- 🚇 **智能隧道代理** �?无需全局 VPN 即可访问受限 API，仅代理 API 流量
- 🧩 **技能浏览器** �?发现、安装和管理 AI 技�?- 🖥�?**本地模型服务�?* �?通过 llama.cpp 本地运行开源模型（Qwen、DeepSeek、Llama�?- 🌍 **28 种语言** �?完整国际化支�?- 🎮 **内置 AI 应用** �?交互�?AI 游戏和工具，�?Reversi �?AI 翻译
- 🌃 **赛博朋克 UI** �?炫酷的霓虹绿终端美学，让编程充满未来�?
## 🖼�?截图

### Model Nexus �?在一处管理所�?AI 模型
![Model Nexus](./1.png)

### App Manager �?一键为所有编程工具切换模�?![App Manager](./2.png)

### Local Server �?通过 llama.cpp 本地运行开源模�?![Local Server](./3.png)

### Skill Browser �?发现和安�?AI 技�?![Skill Browser](./4.png)

## 🚀 快速开�?
### 下载

获取适合你平台的最新版本：

| 平台 | 下载 |
|----------|----------|
| Windows  | [Echobird-Setup.exe](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| macOS    | [Echobird.dmg](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| Linux    | [Echobird.AppImage](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |

### Linux 说明

```bash
chmod +x Echobird-*.AppImage
./Echobird-*.AppImage
```

> 如果遇到 FUSE 错误�?`sudo apt install libfuse2`

## 🔧 支持的工�?
| 工具 | 状�?| 模型切换 | 协议 |
|------|--------|----------------|----------|
| OpenClaw | �?已支�?| �?| OpenAI / Anthropic |
| Claude Code | �?已支�?| �?| Anthropic |
| Cline | �?已支�?| �?| OpenAI |
| Continue | �?已支�?| �?| OpenAI |
| OpenCode | �?已支�?| �?| OpenAI |
| Codex | �?已支�?| �?| OpenAI |
| Roo Code | �?已支�?| �?| OpenAI |

## 🏗�?技术栈

- **Electron** �?跨平台桌面框�?- **React + TypeScript** �?UI 框架
- **Vanilla CSS** �?自定义赛博朋克设计系�?- **Vite** �?构建工具
- **llama.cpp** �?本地模型推理引擎

## 🛠�?开�?
```bash
npm install
npm run dev
npm run build
```

## 🤝 贡献

欢迎贡献！随时提�?Issue �?Pull Request�?
We're especially looking for help with:
- 🍎 **macOS 测试**
- 🔧 **新工具集�?*
- 🌐 **翻译改进**

## �?支持

如果 Echobird 对你有帮助，请在 GitHub 上给�?�?—�?让更多人发现这个项目�?
## 📄 许可�?
[MIT](../LICENSE)

---

<p align="center">
  �?Echobird 团队�?💚 打�?br/>
  <sub>📧 <a href="mailto:hi@echobird.ai">hi@echobird.ai</a></sub>
</p>
