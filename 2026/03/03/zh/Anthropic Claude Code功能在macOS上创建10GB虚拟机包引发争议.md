# Anthropic Claude Code"Cowork"功能未经提示在macOS上创建10GB虚拟机包

有用户发现，Anthropic旗下Claude Code的"Cowork"协作功能会在macOS系统上静默创建一个约10GB的虚拟机捆绑包，事先未明确提示用户，引发关于AI开发工具透明度与资源管理的讨论。

![Claude Code GitHub Issue](https://opengraph.githubassets.com/e617fbb1b08448ad6246dbaea1bac2adebef1b7f1fb7208968cd68b2080fd70d/openclaw/openclaw)

## 事件经过

一名用户在Anthropic的claude-code GitHub仓库中提交了Issue #22543，描述了以下情况：在使用Claude Code的"Cowork"功能（一项允许多人或多代理协同工作的功能）时，系统在macOS上创建了一个约10GB大小的虚拟机捆绑包（VM bundle），且在操作之前未向用户明确提示该行为或告知所需存储空间。

对于普通用户而言，一个应用悄然占用10GB磁盘空间，可能造成存储告急或困惑，尤其是对于容量有限的MacBook用户。该Issue引发了社区其他用户的共鸣，部分人表示遇到了类似的情况。

## 背景与意义

这一问题涉及AI开发工具的"最小惊讶原则"（Principle of Least Astonishment）——用户对工具的行为应有合理预期，任何可能显著影响系统资源（如磁盘空间）的操作都应在执行前明确告知用户并征得同意。

Claude Code是Anthropic面向开发者推出的AI编程代理工具，其"Cowork"功能通过虚拟化环境实现多代理协作，具有技术合理性，但在资源消耗的告知方式上显然存在改进空间。

随着AI工具日益深度集成到开发环境中，"透明度"与"用户控制权"将成为工具设计的核心评价维度之一。

## 延伸阅读

- Anthropic是否计划在后续版本中加入更明确的资源使用提示？
- AI编程代理工具对本地资源的使用应遵循哪些最佳实践？

---

**原文来源：**
- [Anthropic Cowork feature creates 10GB VM bundle on macOS without warning](https://github.com/anthropics/claude-code/issues/22543)
