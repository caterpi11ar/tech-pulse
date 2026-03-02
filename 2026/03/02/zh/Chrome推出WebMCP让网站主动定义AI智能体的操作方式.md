# Chrome 推出 WebMCP，让网站主动定义 AI 智能体的操作方式

谷歌 Chrome 团队宣布 WebMCP 正式进入早期预览阶段。这一新 Web 标准允许网站开发者在页面中声明结构化工具，让 AI 智能体以更精准、更高效的方式与网站交互，无需再通过模拟点击或截图识别等低效手段来完成任务。

![WebMCP Chrome 开发者功能](https://developer.chrome.com/static/blog/webmcp-epp/image/cover.png)

## 功能概述

WebMCP 提出了两套新 API：

**声明式 API（Declarative API）**：允许开发者直接在 HTML 表单中定义标准操作，AI 智能体可直接识别并执行，无需解析页面 DOM 结构。

**命令式 API（Imperative API）**：面向更复杂的动态交互场景，需要 JavaScript 执行，适合需要多步骤逻辑的工作流。

通过这两套 API，网站可以明确告诉 AI 智能体："这里是订机票的入口"、"这是提交工单的操作"，从而实现更可靠、更快速的自动化工作流，取代目前 AI 智能体普遍依赖的视觉截图识别或 DOM 爬取方式。

该功能目前处于早期预览阶段，于 2026 年 2 月 10 日发布。

## 背景与意义

随着 AI 智能体（Agent）越来越多地被用于自动化网页操作，当前的技术方案存在明显短板：AI 要么通过截图"看"页面然后模拟点击，要么爬取 HTML 试图理解页面结构——两种方式都脆弱且低效，一旦页面布局变化就容易失效。

WebMCP 的思路是让网站**主动适配** AI 智能体，而非让 AI 被动适应各种千奇百怪的页面结构。这与 MCP（Model Context Protocol）的理念有相似之处，但 WebMCP 直接面向 Web 标准，嵌入浏览器层面，覆盖面更广。

对用户而言，这意味着未来由 AI 执行的"帮我查一下机票"、"帮我提交这份申请"等任务，将变得更加可靠；对网站开发者而言，提前适配 WebMCP 也意味着在 AI 驱动流量时代获得先发优势。

## 后续关注点

- WebMCP 是否会成为 W3C 正式标准，还是保留为 Chrome 专属特性？
- Safari 和 Firefox 是否会跟进支持？
- 主流网站（电商、SaaS、政府服务）何时会开始大规模采用？

---

**原文来源：** [https://developer.chrome.com/blog/webmcp-epp](https://developer.chrome.com/blog/webmcp-epp)
