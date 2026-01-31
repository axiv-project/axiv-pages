# AXiV Pages（App Store Connect 用）

このリポジトリは、App Store Connect 申請に必要なページ（プライバシーポリシー / サポート）を GitHub Pages で公開するためのものです。

## 作成済みページ

- プライバシーポリシー: `docs/privacy-policy/index.html`
- サポート: `docs/support/index.html`
- 入口ページ: `docs/index.html`

## 公開手順（GitHub Pages）

1. このフォルダを GitHub のリポジトリとして作成し、push します（例: リポジトリ名 `axiv-pages`）。
2. GitHub のリポジトリ設定で **Settings → Pages** を開きます。
3. **Build and deployment** で、Source を `Deploy from a branch` にして、Branch を `main`、Folder を `/docs` に設定します。
4. 表示された公開URLを App Store Connect に設定します。

## App Store Connect に貼る URL（例）

公開URLが `https://<GitHubユーザー名>.github.io/axiv-pages/` の場合:

- Privacy Policy URL: `https://<GitHubユーザー名>.github.io/axiv-pages/privacy-policy/`
- Support URL: `https://<GitHubユーザー名>.github.io/axiv-pages/support/`

## 置き換えが必要な箇所

連絡先メール: `axiv.app.contact@gmail.com`

