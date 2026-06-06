# 你好，我是 lilyzhaun

我主要在做 **AI 工具链、Agent 工作流、模型接入层** 和 **运维/控制面板类产品**。  
关注的方向不是单点模型调用，而是围绕大模型能力构建 **更稳定、可管理、可落地的系统与界面**。

## 我在做什么

目前比较集中的方向包括：

- **Agent / Coding Agent 相关工具**：围绕 OpenCode、Claude Code、Gemini CLI 等工具做可视化、接入层与体验增强
- **OpenAI 兼容代理层**：把不同模型、不同账号体系、不同供应侧能力统一成更易接入的 API
- **自托管控制面板 / Dashboard**：把内部工具做成真正能日常使用的产品界面
- **团队/账号管理工具**：解决多账号、多节点、多服务下的运维与切换问题

## 代表项目

### Agent / 开发者工作流

- **[openchamber](https://github.com/lilyzhaun/openchamber)**  
  OpenCode 的桌面端与 Web 可视化界面，适合把 agent 工作流从命令行延伸到多端操作。

- **[claude-office](https://github.com/lilyzhaun/claude-office)**  
  一个把 Claude Code 操作过程可视化成实时像素办公室的实验性项目。

- **[opencode-cursor](https://github.com/lilyzhaun/opencode-cursor)**  
  通过 HTTP proxy 把 Cursor Pro 模型接入 OpenCode 的尝试。

### 模型接入层 / API 代理

- **[CLIProxyAPI](https://github.com/lilyzhaun/CLIProxyAPI)**  
  将 Gemini CLI、Claude Code、ChatGPT Codex、Qwen Code、iFlow 等工具封装为 OpenAI / Gemini / Claude / Codex 兼容 API。

- **[grok2api](https://github.com/lilyzhaun/grok2api)**  
  基于 FastAPI 的 Grok API 代理，支持流式对话、图像能力、工具调用等特性。

- **[qwen2api](https://github.com/lilyzhaun/qwen2api)**  
  将 Qwen Chat 转换为 OpenAI 兼容 API 的代理服务。

### 面板 / 运维与管理工具

- **[llm-pulse](https://github.com/lilyzhaun/llm-pulse)**  
  面向模型可用性与状态的监控面板，兼顾隐私保护与轻量部署。

- **[Antigravity-Manager](https://github.com/lilyzhaun/Antigravity-Manager)**  
  面向 Antigravity 工作流的账号管理与快速切换工具。

- **[chatgpt-team-helper](https://github.com/lilyzhaun/chatgpt-team-helper)**  
  围绕 Team 账号管理的一站式辅助工具。

## 技术栈

日常用得比较多的技术与组件：

- **前端**：TypeScript、React、Tauri、Web UI / PWA
- **服务端**：Node.js、Python、FastAPI
- **数据层**：PostgreSQL、SQLite
- **部署与运维**：Docker、自托管服务、代理层与多节点管理
- **AI 生态**：OpenAI-compatible API、Agent UX、模型聚合与接入

## 我比较关心的问题

- 如何把“能用的脚本”变成“稳定可维护的产品”
- 如何让 Agent 工作流从命令行扩展到更高效的桌面/移动端交互
- 如何在多模型、多账号、多服务源之间建立统一接入层
- 如何让 AI 工具链更适合长期、自托管、团队化使用

## 关于这个主页

这个主页会优先展示我正在投入维护、持续演进、或者有明确产品方向的项目。  
如果你想快速了解我的工作，建议先看上面的代表项目和置顶仓库。
