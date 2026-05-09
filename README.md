<div align="center">

# 🦊 OpenCode 教程中文版

### 让中文开发者把 OpenCode 装进终端、模型自由、可审批的工作流

> 💎 **不是官方文档的翻译，而是为中文新手重写的双路径教程：理解篇负责心智模型，官方篇负责事实基准——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/opencode)
[![章节](https://img.shields.io/badge/章节-40_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/opencode)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![事实基准](https://img.shields.io/badge/事实基准-OpenCode_官方仓库-FF7A00?style=for-the-badge)](https://github.com/sst/opencode)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/opencode)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **官方文档不缺，中文版翻译也不缺，缺的是「能让中文新手真的读下去并用起来」的版本。**
>
> 这份教程基于 OpenCode 官方仓库源码、文档和发布记录重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 8 篇 **从原理到实战** 帮你建立心智模型，9 个分组的 **官方教程中文版** 覆盖 TUI、Agent、Skills、MCP、模型供应商、SDK 全栈细节。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/opencode) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/opencode/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/opencode/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/opencode-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 OpenCode 学习入口 —— 一站把终端 TUI × 模型供应商策略 × Agent / Skills / MCP × 安全分享全讲透。

这是《AI 编程教程中文版》里的 OpenCode 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/opencode) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解 OpenCode 为什么坚持终端 TUI、为什么要做模型自由 | **8 篇** | [开始 →](https://aiworkflowtutorials.com/docs/opencode/understanding) |
| 📚 **官方教程中文版** | 想直接查 CLI 命令、配置、Agent / Skills / MCP / SDK 用法 | **32 篇** | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：不是机翻，每篇按"先讲场景再讲原理"的顺序，避免源码 + 英文文档双重门槛
- 🦊 **终端原生友好**：聚焦 TUI 工作流，告诉你怎么配键位、怎么做分屏、怎么把 OpenCode 嵌入日常 shell
- 🔌 **模型供应商中立**：Claude / Gemini / GPT / 本地模型 / 自托管 LLM，每种场景给出选型建议
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读官方教程中文版的「**入门**」4 篇，跑通安装、连接模型、第一次启动 TUI
2. 再读从原理到实战 **01-04**，建立 OpenCode 终端工作流、Rules、命令的心智模型
3. 回到真实项目，用一个小改动练习"先 plan 再 apply 再 verify"的闭环
4. 最后进入 **Agents / Skills / Plugins / MCP / SDK**，把重复流程沉淀成可复用能力

### 🧠 从原理到实战（8 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | OpenCode 是什么 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/01-what-is-opencode) |
| 02 | 安装、连接模型与第一次运行 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/02-install-first-run) |
| 03 | 终端 TUI 工作流 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/03-terminal-workflow) |
| 04 | 配置、Rules 与自定义命令 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/04-config-rules-commands) |
| 05 | Agents、Skills 与 Plugins | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/05-agents-skills-plugins) |
| 06 | 模型与供应商策略 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/06-model-provider-strategy) |
| 07 | 工具、MCP、LSP 与格式化器 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/07-tools-mcp-lsp) |
| 08 | 安全、分享与团队使用 | [阅读 →](https://aiworkflowtutorials.com/docs/opencode/understanding/08-security-share-team) |

### 📚 官方教程中文版（9 个分组 · 32 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **入门** | 安装、首次运行、TUI 基础 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/00-getting-started) |
| 🛠️ **自定义** | 配置文件 / Rules / 命令绑定 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/01-customization) |
| 🤖 **Agents 与 Skills** | Agent 定义 / Skills 编写 / 任务编排 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/02-agents-skills) |
| 🧠 **模型** | 多供应商配置 / 路由策略 / 本地模型接入 | 2 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/03-models) |
| 🔌 **工具与 MCP** | 工具调用 / MCP 服务接入 / LSP 集成 | 5 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/04-tools-mcp) |
| 🔒 **安全** | 沙箱 / 审批 / 凭据隔离 | 2 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/05-security) |
| 🔗 **集成** | Editor 插件 / Git / CI / Shell | 4 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/06-integrations) |
| 📦 **SDK** | 编程方式调用 OpenCode 的接口 | 3 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/07-sdk) |
| 🌐 **平台** | 团队 / 多机器 / 远端运行场景 | 4 | [开始 →](https://aiworkflowtutorials.com/docs/opencode/official/08-platform) |

### 💡 第一次在项目里用 OpenCode

```text
你（在终端启动 opencode 后）：

  我在 ~/projects/{repo}，先读 README、配置文件和入口模块，
  告诉我这个项目是干什么的，主要模块怎么分工。
  接着提出三个最小的可改进点（每条不超过 1 行），
  我选一个之后你再写 plan，我确认后再 apply。
```

> 🎯 **OpenCode 的优势是终端原生 + 模型自由**——配好供应商后，可以根据任务类型在 Claude / Gemini / GPT 之间一键切换，不用换工具。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：`sst/opencode` 仓库发布或文档结构调整的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/opencode-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + 多 Agent 编排模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
