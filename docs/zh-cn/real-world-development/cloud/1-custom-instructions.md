---
title: "练习 1 - 自定义指令（云智能体）"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[← 上一课：先决条件][previous-lesson] · [下一课：GitHub Copilot 云智能体 →][next-lesson]

上下文是使用生成式 AI 的关键。通过存储库级自定义指令和路径范围指令文件，为 Copilot 提供项目背景、编码规范和文档要求。

## 指令文件

在本练习中，查看 `.github/copilot-instructions.md` 和 `.github/instructions/` 中的文件，并了解如何为不同任务提供上下文。

## 添加存储库标准

在 **Code formatting requirements** 下添加以下规则：

```markdown
- Every exported function should have a TSDoc comment describing its purpose, parameters, and return value.
- Before imports or any code, add a comment block to the file that explains its purpose.
```

提交、推送并合并更改，使云智能体在后续练习中读取这些指令。

## 总结和下一步

你已了解 Copilot 如何读取上下文，并添加了存储库级标准。接下来，[将第一个议题分配给云智能体][next-lesson]。

[previous-lesson]: ../0-prerequisites/
[next-lesson]: ../2-cloud-agent/
