# OpenCode 入门 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <strong>简体中文</strong> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>最聪明的代码助手需要最安全的边界。</strong></h3>
  <p><strong>针对 OpenCode.ai 代理生态系统进行优化的高性能、模块化入门模板，具有安全的精细权限和内置诊断控制功能。</strong></p>

  <p>不再担心 AI 代理执行破坏性终端命令或泄漏私有环境变量。体验安全、高速的自主编码。</p>
</div>

> 📦 **andiupn** 提供的免费模板 ([kuncimu.com](https://kuncimu.com)) · 根据 [MIT 许可证](LICENSE) 获得许可  
> ☕ 如果有用，[请我喝杯咖啡](https://ko-fi.com/andiupn) · 🚀 需要更多功能？尝试[专业版](https://github.com/sponsors/andiupn?frequency=monthly)

__徽章_0__
__徽章_1__
__徽章_2__
__徽章_3__
__徽章_4__
__徽章_5__

---

欢迎使用 **OpenCode Starter**，这是一个实验性模块化工作空间配置，针对使用 OpenCode.ai 平台与 AI 代理进行协作进行了优化。凭借安全的访问控制准则和高度精确的代理角色划分，您可以更快、更安全且完全控制地构建任何项目。

---

## 💡 问题：“自主风险”
完全自主的人工智能代理非常强大，但它们也带来了风险。如果没有边界，代理可能会运行有害的 bash 命令、意外删除系统配置或读取/暴露您的私有 `.env` 文件。

---

## ⚡ 解决方案：受保护的高速自治

### 1. 🛡️ 精细的权限保障
`opencode.json` 中预先配置的安全准则明确拒绝访问敏感文件（如 `.env`），同时安全地自动允许 git 和 grep 操作。高速，零安全焦虑。

### 🤖 2. 5 个模块化 AI 角色
组建一支由 5 个自主代理组成的有组织的专业团队，直接在 `.opencode/agents/` 中进行配置：
- **`code`** — 安全地编写和编辑代码。
- **`research`** — 探索和映射代码库架构。
- **`debug`** 和 **`refactor`** — 诊断、修复和清理优化。
- **`document`** — 维护文档而不污染代码。

### 🌐 3.内置斜线诊断
即时执行命令，如 `/analyze` 来映射项目结构，`/fix` 来扫描和修复错误，以及 `/explain` 在几毫秒内分解复杂文件。

---

## 📊 LITE 与 PRO：高级升级

`opencode-starter` 被设计为一个干净的基线。对于专业的 monorepos 和高级工作流程：

|特色 | 🆓 LITE（入门版）| 💎 PRO（高级）|
|---|:---:|:---:|
| **专业代理** | 5（代码、研究等）| 5（模块化系统）|
| **工作流程技能** | 2（`coding-conventions`，`testing`）| 15+（数据库、操作等）|
| **工作区结构** |简单|状态优先 Monorepo（`active/` 等）|
| **项目预设** | ❌ | 10 个预设（Next、Laravel、Flutter 等）|
| **操作和服务器同步** | ❌ | ✅（Docker Compose 和 Caddyfile 就绪）|

👉 **[查看完整比较和升级指南](COMPARISON.md)**

---

## 📂 存储库结构

__代码_块_0__

---

## 🚀 快速入门

### 1.复制并设置环境
复制您的项目环境变量模板：

__代码_块_1__

打开 `.env` 文件并插入 `GITHUB_TOKEN` 以启用存储库集成。

### 2. 开始代理协作
启动 OpenCode AI Agent CLI 或在 AI 友好的编辑器中加载 `opencode.json` 配置文件。使用以下内置命令：
- **项目分析：** `/analyze`
- **诊断和修复漏洞：** `/fix`
- **解释模块：** `/explain [filename]`

---

## 💖 支持这个项目（捐款）

如果此入门模板有助于加快您的编码工作流程，请考虑通过以下链接提供支持或捐赠：
- **Ko-fi：** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon：** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer：** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria：** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 许可证

该项目根据 **MIT 许可证** 获得许可。有关详细信息，请参阅 [LICENSE](LICENSE) 文件。