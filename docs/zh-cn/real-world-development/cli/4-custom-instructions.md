---
title: "练习 4 - 使用自定义指令指导 Copilot"
description: "探索存储库指令、添加文档标准，并将其应用于筛选代码。"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

了解 Copilot 如何读取存储库级和路径范围指令。查看 `.github/copilot-instructions.md` 及 `.github/instructions/` 中的文件，然后添加 TSDoc 文档标准并重新运行筛选任务。

## 场景

Tailspin Toys 要求注释说明意图和不明显的决策，并为 `db/` 和 `src/lib/` 中导出的函数记录用途、参数和返回值。使用指令文件可以让 Copilot 按照这些规范工作。

## 更新指令

在 **Code formatting guidance** 部分添加以下规则：

```markdown
- All new TypeScript should contain TSDocs comments for documentation purposes.
```

保存后重新开始或恢复 Copilot CLI 会话，让它加载更新后的指令并审查生成的差异。

## 总结和下一步

你已了解 Copilot CLI 如何读取指令，并将新的文档标准应用到筛选功能。接下来，使用[可复用的质量检查技能][next-lesson]。

[next-lesson]: ../5-agent-skills/
