<div align="center">

# 🚀 Awesome AI Developer Arsenal

**A curated list of modern AI tools, agent workflows, and productivity prompts for developers.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintained by Laurent](https://img.shields.io/badge/Maintained%20by-Laurent-blue)](https://github.com/laurentshowtime)

[English](./README_EN.md) | [简体中文](./README.md)

</div>

---

## 📌 Why This Repository?

AI is reshaping the software development lifecycle. Initiated by [@laurentshowtime](https://github.com/laurentshowtime), this project curates and maintains modern AI tools, agent workflows, and best practices that deliver real productivity gains.

⭐️ **Star this repo** to stay updated with the latest AI dev trends!

---

## 📑 Table of Contents

- [💻 AI Coding Assistants & IDEs](#-ai-coding-assistants--ides)
- [🤖 AI Agents & Autonomous Frameworks](#-ai-agents--autonomous-frameworks)
- [🛠️ Developer Productivity & Debugging Tools](#️-developer-productivity--debugging-tools)
- [📝 Featured System Prompts & Cursor Rules](#-featured-system-prompts--cursor-rules)
- [🤝 Contributing](#-contributing)

---

## 💻 AI Coding Assistants & IDEs

| Tool | Category | Highlights | Website |
| :--- | :--- | :--- | :--- |
| **Cursor** | AI IDE | Deep VS Code integration, whole-codebase reasoning | [Visit](https://cursor.com) |
| **Claude Code** | CLI Assistant | Interactive full-terminal coding, debugging & refactoring | [Visit](https://anthropic.com) |
| **v0 by Vercel** | UI Generation | Generates modern React & Tailwind UI components | [Visit](https://v0.dev) |
| **Continue** | Open Source Extension | Connect local LLMs (Ollama / vLLM) as your copilot | [Visit](https://github.com/continuedev/continue) |

---

## 🤖 AI Agents & Autonomous Frameworks

- [**Agent QA**](https://github.com/vostride/agent-qa) - Authors and runs natural-language regression tests for web, Android, and iOS. Source-available under FSL-1.1-ALv2; each release converts to Apache-2.0 after two years.
- [**LangGraph**](https://github.com/langchain-ai/langgraph) - Build cyclical, multi-agent workflows with fine-grained state control.
- [**AutoGPT / Forge**](https://github.com/Significant-Gravitas/AutoGPT) - The pioneer autonomous AI agent architecture.
- [**CrewAI**](https://github.com/joaomdmoura/crewAI) - Role-playing, collaborative multi-agent orchestration framework.

---

## 📝 Featured System Prompts & Cursor Rules

<details>
<summary><b>🔍 Click to expand: Senior Code Reviewer Prompt</b></summary>

```markdown
You are a meticulous principal engineer reviewing code changes. Provide structured feedback:
1. Potential bugs and edge-case vulnerabilities
2. Performance and memory optimization opportunities
3. Readability and idiomatic naming conventions
4. Clear before/after diff code snippets
