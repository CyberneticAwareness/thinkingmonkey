

<h1 align="center">
<img src="./src/assets/logo.png"/><br/>
ThinkingMonkey
</h1>

<p align="center">
ThinkingMonkey is an open-source userscript manager and automation engine.<br/>
It extends the Tampermonkey / Violentmonkey model with <b>agentic background scripts</b>,
<b>cross-tab communication</b>, and <b>programmable browser cognition</b>.
</p>

<p align="center">
<a href="https://github.com/CyberneticAwareness/thinkingmonkey">GitHub</a> ·
<a href="#">Documentation (WIP)</a> ·
<a href="#">Community (WIP)</a>
</p>

![GitHub stars](https://img.shields.io/github/stars/CyberneticAwareness/thinkingmonkey.svg)
[![Build Status](https://github.com/CyberneticAwareness/thinkingmonkey/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/CyberneticAwareness/thinkingmonkey/actions)
![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/CyberneticAwareness/thinkingmonkey.svg?label=version)

---

## 🧠 About ThinkingMonkey

ThinkingMonkey is a **next-generation userscript platform** inspired by Tampermonkey,
Violentmonkey, and modern agent frameworks.

Unlike traditional userscript managers that operate *per page*,
ThinkingMonkey treats the browser as a **multi-tab, multi-agent environment**.

Scripts can:
- run in the background
- communicate across tabs
- coordinate actions between different websites
- act as long-lived browser agents

This makes ThinkingMonkey suitable for:
- AI tab-casting
- MCP-style browser orchestration
- cross-site automation
- research workflows
- power-user augmentation

---

## ✨ Core Concepts

### 🧩 Agentic Scripts

- Scripts are not limited to a single page lifecycle
- Background scripts can persist, observe, and react
- Explicit APIs for coordination and signaling

### 🔁 Cross-Tab Communication

- Tabs are first-class addressable entities
- Scripts can send structured messages between tabs
- Enables “output from one site → input to another”

### 🔧 Tampermonkey Compatibility

- High compatibility with existing Tampermonkey scripts
- Familiar `GM_*` API surface
- Progressive extension with new primitives

### 🛡️ Security Model

- Sandboxed script execution
- Explicit permission declarations
- Clear separation between page, content, and background contexts

---

## 🚀 Status

ThinkingMonkey is **early-stage and experimental**.

Current focus:
- minimal, rigorous API extensions
- one new primitive per iteration
- correctness > feature count

This is not a script marketplace yet.
This is infrastructure.

---

## 🤝 Contributing

ThinkingMonkey welcomes contributors who care about:
- clean abstractions
- browser internals
- automation ethics
- agent architectures

Expect rapid iteration and breaking changes.

---

## 📄 License

ThinkingMonkey is open-source software licensed under **GPLv3**.
Please comply with the license when modifying or redistributing.

---

> 🐒 ThinkingMonkey is not about scripting pages.  
> It is about teaching the browser how to think.
