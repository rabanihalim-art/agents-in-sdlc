---
title: "レッスン 4 - カスタム命令"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

Copilot CLI にプロジェクト固有のコンテキストを渡すため、リポジトリ命令とパス単位の instruction file を確認します。

## 手順

1. `.github/copilot-instructions.md` と `.github/instructions/` を開きます。
2. 現在の命令を使って publishers helper を生成します。
3. `.github/copilot-instructions.md` に、エクスポートされた関数の TSDoc とファイルヘッダーを追加します。
4. 同じプロンプトを再実行し、生成コードが新しい標準に従うことを確認します。
5. 命令と helper をコミットします。

> [!NOTE]
> Copilot は確率的に動作するため、生成結果は例と完全には一致しません。出力の傾向と要件への適合をレビューしてください。

## 次のステップ

[Playwright MCP で機能を検証する][next-lesson]に進みます。

[next-lesson]: ../6-mcp-playwright/
