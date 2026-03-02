<p align="center">
  <img src="./icon.png" alt="Echobird" width="120" />
</p>

<h1 align="center">Echobird</h1>

<p align="center">
  The Nexus for <strong>Models</strong>, <strong>Agents</strong> & <strong>Vibe Coding</strong>.<br/>
  <sub>Echobird は、AIコーディングツール全体でモデルを管理するためのビジュアルで統一されたインターフェースを提供するデスクトップアプリです�?/sub>
</p>

<p align="center">
  <a href="https://github.com/edison7009/Echobird-MotherAgent/releases">
    <img src="https://img.shields.io/github/v/release/edison7009/Echobird-MotherAgent?style=flat-square&color=00FF9D" alt="Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/github/license/edison7009/Echobird-MotherAgent?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="./README.md">English</a> · <a href="./README.zh-CN.md">简体中�?/a> · <a href="./README.zh-TW.md">繁體中文</a> · **日本�?* · <a href="./README.ko.md">한국�?/a>
</p>

---

## �?Echobird とは�?
Echobird は、AIコーディングツール全体でモデルを管理するため�?*ビジュアルで統一されたインターフェー�?*を提供するデスクトップアプリです�?
### 課題

- 😫 OpenClaw などのツールでAIモデルを切り替えるには設定ファイルの手順が必�?- 🔄 各ツールが独自のモデル設定形式を持ってい�?- 🧩 ツール間でスキルや拡張機能を管理する方法がな�?
### ソリューショ�?
Echobird はすべてのAIコーディングツールの**中央コントロールパネ�?*として機能します�?
- 🎯 **ワンクリックモデル切�?* �?対応ツールのAIモデルをビジュアルに切り替え
- 🔀 **デュアルプロトコ�?* �?OpenAI & Anthropic API対応
- 🚇 **スマートトンネルプロキシ** �?フルVPNなしで地域制限APIにアクセ�?- 🧩 **スキルブラウ�?* �?AIスキルを発見、インストール、管�?- 🖥�?**ローカル模型サーバー** �?llama.cpp経由でオープンソースモデルをローカル実行
- 🌍 **28言語対�?* �?グローバル対応の完全国際�?- 🎮 **内蔵AIアプ�?* �?Reversi やAI翻訳などのインタラクティブなAIゲー�?- 🌃 **サイバーパン�?UI** �?ネオングリーンのターミナル美�?
## 🖼�?スクリーンショッ�?
### Model Nexus �?すべてのAIモデルを一箇所で管�?![Model Nexus](./1.png)

### App Manager �?ワンクリックでモデル切替
![App Manager](./2.png)

### Local Server �?オープンソースモデルをローカル実�?![Local Server](./3.png)

### Skill Browser �?スキルを発見・インストー�?![Skill Browser](./4.png)

## 🚀 クイックスタート

### ダウンロー�?
最新リリースを入手�?
| プラットフォーム | ダウンロー�?|
|----------|----------|
| Windows  | [Echobird-Setup.exe](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| macOS    | [Echobird.dmg](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |
| Linux    | [Echobird.AppImage](https://github.com/edison7009/Echobird-MotherAgent/releases/latest) |

### Linux の注意事�?
```bash
chmod +x Echobird-*.AppImage
./Echobird-*.AppImage
```

> FUSE エラーが発生した場合�?`sudo apt install libfuse2`

## 🔧 対応ツー�?
| ツー�?| ステータ�?| モデル切�?| プロトコ�?|
|------|--------|----------------|----------|
| OpenClaw | �?対応済み | �?| OpenAI / Anthropic |
| Claude Code | �?対応済み | �?| Anthropic |
| Cline | �?対応済み | �?| OpenAI |
| Continue | �?対応済み | �?| OpenAI |
| OpenCode | �?対応済み | �?| OpenAI |
| Codex | �?対応済み | �?| OpenAI |
| Roo Code | �?対応済み | �?| OpenAI |

## 🏗�?技術スタッ�?
- **Electron** �?デスクトップフレームワー�?- **React + TypeScript** �?UIフレームワー�?- **Vanilla CSS** �?デザインシステム
- **Vite** �?构建工具
- **llama.cpp** �?推論エンジン

## 🛠�?開発

```bash
npm install
npm run dev
npm run build
```

## 🤝 コントリビュート

コントリビュート大歓迎！

We're especially looking for help with:
- 🍎 **macOS 测试**
- 🔧 **新工具集�?*
- 🌐 **翻译改进**

## �?サポート

Echobird が役立ったら、GitHub �?�?をお願いします！

## 📄 ライセン�?
[MIT](../LICENSE)

---

<p align="center">
  Echobird チームが 💚 を込めて制作<br/>
  <sub>📧 <a href="mailto:hi@echobird.ai">hi@echobird.ai</a></sub>
</p>
