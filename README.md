# OpenCode Starter 🚀

<div align="center">
  <strong>English</strong> | <a href="README.id.md">Bahasa Indonesia</a>
</div>

<br />

**A high-performance, modular starter template optimized for the OpenCode.ai agent ecosystem.**

> 📦 Free template by **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensed under [MIT License](LICENSE)  
> ☕ If useful, [buy me a coffee](https://ko-fi.com/andiupn) · 🚀 Need more features? Try the [PRO version](https://kuncimu.com)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Welcome to **OpenCode Starter**, an experimental modular workspace configuration optimized for collaborating with AI Agents using the OpenCode.ai platform. Featuring secure access control guidelines and highly precise division of agent roles, you can build any project faster, safer, and with complete control.

---

## 🌟 Key Features

- **Modular AI Roles:** 5 built-in specialized agents configured autonomously in `.opencode/agents/` (Code, Research, Debug, Refactor, Document).
- **Granular Permissions:** Secure access control model in `opencode.json` that limits bash execution and blocks unauthorized access to sensitive files (such as `.env`).
- **Standard Commands:** Built-in slash commands like `/analyze`, `/fix`, and `/explain` for instant project diagnostics.
- **Experimental Scaffold:** Highly modular and ready to scaffold multi-language projects and frameworks.

---

## 📂 Repository Structure

```
your-workspace/
  .opencode/           # OpenCode agent rules, automation skills, and prompts
    agents/            # Instruction directives for 5 AI agents
    skills/            # Coding conventions and testing guides
  .env.example         # Template for environment variables
  .gitignore           # Standard Git ignore file
  AGENTS.md            # Master rules for AI Agents
  opencode.json        # OpenCode permissions, model selection, and command maps
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Quick Start

### 1. Copy and Setup Environment
Copy your project environment variables template:
```bash
cp .env.example .env
```
Open the `.env` file and insert your `GITHUB_TOKEN` to enable repository integrations.

### 2. Begin Agent Collaboration
Launch the OpenCode AI Agent CLI or load the `opencode.json` configuration file in your AI-friendly editor. Utilize the following built-in commands:
- **Project Analysis:** `/analyze`
- **Diagnose & Fix Vulnerabilities:** `/fix`
- **Explain Module:** `/explain [filename]`

---

## 📊 LITE vs PRO Comparison

`opencode-starter` is designed to be a clean baseline. For professional monorepos and advanced workflows:

| Feature | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Specialized Agents** | 5 (Code, Research, etc.) | 5 (Modular System) |
| **Workflow Skills** | 2 (`coding-conventions`, `testing`) | 15+ (Database, Ops, etc.) |
| **Workspace Structure** | Simple | Status-first Monorepo (`active/`, etc.) |
| **Project Presets** | ❌ | 10 Presets (Next, Laravel, Flutter, etc.) |
| **Ops & Server Sync** | ❌ | ✅ (Docker Compose & Caddyfile ready) |

👉 **[View Full Comparison & Upgrade Guide](COMPARISON.md)**

---

## 💖 Support This Project (Donations)

If this starter template helps speed up your coding workflow, consider supporting or donating via the following links:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

Your support is highly valued and helps us maintain and improve AI template integrations in the future! ❤️

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.
