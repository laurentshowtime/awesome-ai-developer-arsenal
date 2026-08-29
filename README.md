# awesome-ai-developer-arsenal
🚀 A curated list of modern AI tools, agent workflows, and productivity prompts for developers. / 专为开发者打造的现代 AI 工具、智能体工作流与提效指南。
<div align="center">

# 🚀 Awesome AI Developer Arsenal

**精选 AI 时代开发者必备工具、自动化工作流与实战指南**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintained by Laurent](https://img.shields.io/badge/Maintained%20by-Laurent-blue)](https://github.com/laurentshowtime)

[English](./README_EN.md) | [简体中文](./README.md)

</div>

---

## 📌 为什么建立这个仓库？

AI 正在重塑软件开发的整个生命周期。本项目由 [@laurentshowtime](https://github.com/laurentshowtime) 发起，致力于收集、整理和持续更新**真正能提升开发效率的 AI 工具、智能体工作流（AI Agents）以及最佳实践**。

欢迎 ⭐️ **Star** 收藏，随时追踪最新更新！

---

## 📑 目录

- [💻 AI 编程助手与 IDE](#-ai-编程助手与-ide)
- [🤖 智能体与自主编码框架](#-智能体与自主编码框架)
- [🛠️ 开发提效与调试工具](#️-开发提效与调试工具)
- [📝 精选 System Prompts & Cursor Rules](#-精选-system-prompts--cursor-rules)
- [🤝 参与贡献](#-参与贡献)

---

## 💻 AI 编程助手与 IDE

| 工具名称 | 分类 | 特性亮点 | 官网链接 |
| :--- | :--- | :--- | :--- |
| **Cursor** | AI IDE | 基于 VS Code 深度集成，全代码库理解与交互 | [访问](https://cursor.com) |
| **Claude Code** | CLI 助手 | 终端内的交互式全流程代码生成与重构 | [访问](https://anthropic.com) |
| **v0 by Vercel** | 前端生成 | 生成现代 React / Tailwind UI 组件与完整页面 | [访问](https://v0.dev) |
| **Continue** | 开源插件 | 支持连接本地大模型（Ollama/vLLM）的代码副驾驶 | [访问](https://github.com/continuedev/continue) |

---

## 🤖 智能体与自主编码框架

- [**Agent QA**](https://github.com/vostride/agent-qa) - 使用自然语言编写并运行 Web、Android 和 iOS 回归测试。当前采用 FSL-1.1-ALv2 源码可用许可证；每个版本将在两年后转换为 Apache-2.0。
- [**LangGraph**](https://github.com/langchain-ai/langgraph) - 构建具有循环、分支与状态管理的多智能体系统。
- [**AutoGPT / Forge**](https://github.com/Significant-Gravitas/AutoGPT) - 经典自主智能体架构探索。
- [**CrewAI**](https://github.com/joaomdmoura/crewAI) - 角色驱动的多 Agent 协同编排框架。

---

## 📝 精选 System Prompts & Cursor Rules

这里收录经过实战检验的高质量 Prompt：

<details>
<summary><b>🔍 展开查看：极致代码审查审查员 (Code Reviewer) Prompt</b></summary>

```markdown
你是一位极其严谨的资深工程师，负责审查提交的代码。请从以下维度输出反馈：
1. 潜在 Bug 与边界条件风险
2. 性能与内存优化空间
3. 代码可读性与命名规范
4. 提供重构前后的 Diff 代码片段
