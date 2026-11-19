---
title: "レッスン 8 - 機能 PR を作成してマージする"
description: "機能変更、命令、スキル、QA プロファイル、テストをまとめてレビューし、Agent Merge を使います。"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

フィルタリング機能と関連する命令、スキル、QA プロファイル、テストをまとめてレビューし、プルリクエストを作成します。

## Agent Merge を使う

**Agent Merge** は、CI チェックの修正、レビューコメントへの対応、必要な rebase など、PR をマージするまでの作業を自動化します。

1. Codespace に戻ります。
2. `/agent` で **Default** を選択します。
3. `/pr create` で PR を作成します。
4. レビューが完了したら `/pr agentmerge` を実行します。
5. 必須チェックと権限の状態を確認し、マージ結果を確認します。

> [!IMPORTANT]
> Agent Merge は、必須承認、ブランチ保護、マージキュー、リポジトリ設定、権限を回避しません。

## 次のステップ

[CLI のパワーツール][next-lesson]に進みます。

[previous-lesson]: ../7-qa-agent/
[next-lesson]: ../9-cli-power-tools/
