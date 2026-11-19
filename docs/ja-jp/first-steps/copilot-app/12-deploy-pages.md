---
title: "レッスン 12 - GitHub Pages でサイトをデプロイする"
description: "GitHub Copilot app を使って Pages ワークフローを設定し、Space Quiz の公開を確認します。"
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Space Quiz を GitHub Pages にデプロイして公開します。Copilot がワークフローの準備を支援しますが、変更をレビューし、サイトが公開されたことを確認する責任は利用者にあります。

## デプロイを準備する

> [!WARNING]
> プルリクエストの作成では、コードのコミットとプッシュが行われる場合があります。プロンプトを送る前に、承認設定と対象リポジトリを確認してください。

`space-quiz` の Copilot app セッションで、次のプロンプトを送信します。

```text
Prepare a GitHub Pages deployment for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages after changes reach the default branch. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and report its link and any required Pages settings or permissions. Do not merge, enable auto-merge, change Pages settings, or deploy. Stop and wait for my review.
```

## ワークフローとプルリクエストをレビューする

1. README は、まだ存在しない場合にだけ追加されていることを確認します。
2. ワークフローのビルド、デプロイ、トリガー、権限を確認します。
3. デフォルトブランチからデプロイされ、未マージのプルリクエストからはデプロイされないことを確認します。
4. 必須チェックが成功してからマージを承認します。

## デプロイを確認する

1. GitHub Actions のデプロイ実行が成功するまで確認します。
2. 報告された URL を開き、Space Quiz が読み込まれることを確認します。

## まとめと次のステップ

Space Quiz を公開し、エージェントの報告だけに頼らず、実際にサイトを確認しました。次は[レッスン 13: レビューと次のステップ][next-lesson]に進みます。

[next-lesson]: ../13-review/
