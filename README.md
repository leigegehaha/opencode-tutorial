# OpenCode 学习教程

从零开始掌握开源终端 AI 编程助手 OpenCode，支持 75+ AI 模型，终端原生体验，隐私优先设计。

## 在线预览

👉 **[点击这里查看教程](https://leigegehaha.github.io/opencode-tutorial/)**

## 内容大纲

- **快速开始**：安装环境、5分钟上手
- **入门篇**：基础命令、模型配置、工作模式
- **中级篇**：配置详解、自定义命令、快捷键
- **高级篇**：技术架构、本地模型、MCP 集成、隐私安全
- **附录**：速查表、常见问题

---

## 🆓 什么是 OpenCode？

OpenCode 是一款开源的、终端优先的 AI 编程助手（智能体），具备以下特点：

- **完全免费开源**，MIT 许可证
- **供应商无关**：支持 Claude、GPT-4、Gemini 或本地模型（如 Ollama）
- **终端原生**，拥有美观的 TUI（终端用户界面）
- **支持 IDE 集成**（VS Code、Cursor 等）
- **隐私优先**：代码不会离开本地，支持完全离线运行

## ⬇️ 快速安装

```bash
# 一键安装
curl -fsSL https://opencode.ai/install | bash

# Homebrew
brew install opencode-ai/tap/opencode

# npm
npm install -g opencode-ai@latest
```

## 🤖 支持的模型

| 提供商 | 模型示例 | 环境变量 |
|--------|----------|----------|
| Anthropic | Claude 3.7 Sonnet, Claude 3.5 Haiku | `ANTHROPIC_API_KEY` |
| OpenAI | GPT-4.1, GPT-4o, O1/O3 | `OPENAI_API_KEY` |
| Google | Gemini 2.5 Pro, Gemini 2.5 Flash | `GEMINI_API_KEY` |
| GitHub Copilot | GPT-4o, Claude 3.5 Sonnet | `GITHUB_TOKEN` |
| Groq | Llama 4, Deepseek R1 | `GROQ_API_KEY` |
| 本地模型 | CodeLlama, DeepSeek-Coder | `LOCAL_ENDPOINT` |

## 🔄 工作模式

OpenCode 提供两种工作模式：

- **🧠 计划模式 (Plan)**：只读分析代码，制定实现方案
- **🔨 构建模式 (Build)**：可读写文件，执行修改

使用 **Tab** 键在两种模式间切换。

## 特色

- 📱 响应式设计，支持手机/平板/电脑
- 🎨 深色主题，保护眼睛
- 🖼️ 10+ 原创 SVG 架构图
- 🔄 交互式 Tab 切换和手风琴组件
- 📋 一键复制代码块
- 🔍 侧边栏搜索导航
- 🆓 完全开源免费

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/leigegehaha/opencode-tutorial.git

# 直接用浏览器打开
open index.html
```

## 相关链接

- [OpenCode 官网](https://opencode.ai)
- [OpenCode GitHub](https://github.com/opencode-ai/opencode)
- [Crush（新项目）](https://github.com/charmbracelet/crush)

---

📗 OpenCode 学习教程 · 开源免费 · 隐私优先
