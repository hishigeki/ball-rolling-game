# ball-rolling-game

このリポジトリはシンプルなスマホ向けボール転がしゲームです。

## Web に公開する方法

このリポジトリを `main` ブランチへ push すると、GitHub Actions が自動で GitHub Pages にデプロイします。

- デプロイ用ワークフロー: `.github/workflows/deploy.yml`
- 公開 URL はリポジトリの `Settings → Pages` で確認できます（通常は `https://<ユーザー名>.github.io/<リポ名>/`）。

手順:

1. この変更をコミットして `origin/main` に push します:

```
git add -A
git commit -m "Add GitHub Pages deploy workflow"
git push origin main
```

2. GitHub Actions が走り、完了すると Pages サイトが公開されます。Actions の実行結果や Pages 設定は GitHub 上で確認してください。
