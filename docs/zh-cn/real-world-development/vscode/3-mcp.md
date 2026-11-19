---
title: "练习 3 - 使用 Playwright MCP 服务器测试功能"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

了解 Model Context Protocol (MCP)，在 `.vscode/mcp.json` 中添加 Playwright MCP 服务器，并让 Copilot 在真实浏览器中验证筛选功能。

```json
{
  "servers": {
    "playwright": {
      "command": "npx",
      "args": ["@playwright/mcp@latest", "--headless"]
    }
  }
}
```

让 Copilot 打开 `http://localhost:4321`，依次测试类别、发行商以及组合筛选，然后审查结果并创建拉取请求。

[previous-lesson]: ../2-agent-mode/
[next-lesson]: ../4-custom-agents/
