# MCP 是否已经死亡？技术博主称 CLI 才是 AI 工具集成的正确姿势

一篇题为《MCP 已死，CLI 万岁》的博客文章在 Hacker News 引发广泛讨论。作者认为，Model Context Protocol（MCP）在实际工程中并未带来真正价值，而命令行工具（CLI）才是让 AI 模型使用外部工具的更好方式。

![MCP 与 CLI 之争](https://plus.unsplash.com/premium_photo-1681487637194-5ff8e1b82143?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wxMjA3fDB8MXxzZWFyY2h8MXx8YXJ0aWZpY2lhbCUyMGludGVsbGlnZW5jZSUyMHRlY2hub2xvZ3l8ZW58MHwwfHx8MTc3MjMzMzc3Nnww&ixlib=rb-4.1.0&q=80&w=1080)

## 文章核心观点

作者 EJ Holmes 的核心论点是：**LLM 本就擅长使用命令行工具，MCP 并未带来真正的增量价值。**

他指出，大型语言模型在训练数据中已经见过海量的命令行文档、Stack Overflow 回答和 shell 脚本，只需给它们一个 CLI 工具和文档，它们就能自己搞定。而 MCP 虽然承诺提供"更干净的接口"，但在实践中，开发者往往还是需要为每个工具编写同等数量的文档——究竟应该调用什么工具、什么参数、什么时机，这些语义信息 MCP 并没有帮你省去。

作者还强调了 CLI 的**可调试性**优势：当 AI 用 CLI 做了某件事，人类可以直接运行同一条命令看到同样的结果，调试直观透明；而 MCP 引入了新的抽象层，出问题时更难定位。

文章还提到，已有若干主流 AI 工具选择不支持 MCP，这本身也是一种市场信号。

## 背景与意义

MCP 由 Anthropic 于 2024 年末发布，旨在为 AI 模型提供一套标准化的工具调用协议。发布之初，整个 AI 行业争相宣称自己"支持 MCP"，各大公司纷纷发布 MCP 服务端。

然而一年多过去，MCP 的实际落地情况参差不齐。批评者认为它在架构上增加了不必要的复杂度，带来了新的授权、安全和维护负担；支持者则认为，对于需要精确工具描述和参数验证的复杂场景，MCP 仍然有其价值。

这场争论的实质，是 AI 时代工具集成的**哲学之争**：应该让 AI 系统用人类已有的工具接口，还是为 AI 专门设计新的通信协议？

## 后续关注点

- Anthropic 是否会回应此类批评，或对 MCP 进行重大调整？
- 随着 AI 智能体越来越复杂，CLI 方式是否会遭遇新的扩展性瓶颈？
- 行业是否会出现"MCP vs CLI"的明显分化？

---

**原文来源：** [https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html](https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html)
