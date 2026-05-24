# ハイモナビ 法的文書サイト

モバイルアプリ「ハイモナビ（HiMo Navi）」の法的文書サイトです。

## 公開URL

- トップ: https://himonavi-legal.pages.dev/
- 特定商取引法に基づく表記: https://himonavi-legal.pages.dev/tokushoho
- プライバシーポリシー: https://himonavi-legal.pages.dev/privacy-policy
- 利用規約: https://himonavi-legal.pages.dev/terms
- お問い合わせ: https://himonavi-legal.pages.dev/contact

## 開発

```sh
npm install
npm run dev
```

## ビルド

```sh
npm run build
```

静的ファイルは `dist/` に生成されます。

## 手動デプロイ

```sh
npm run build
npx wrangler pages deploy ./dist --project-name=himonavi-legal --branch=main
```

## 今後の更新手順

1. `src/pages/` 配下の対象Markdownを編集します。
2. `npm run build` でビルド確認します。
3. `git add .`、`git commit -m "Update legal docs"`、`git push origin main` を実行します。
4. Cloudflare Pages のGitHub連携設定後は、`main` ブランチへのpushで自動再デプロイされます。

## ストア・広告管理画面に登録するURL

- 特商法表記: https://himonavi-legal.pages.dev/tokushoho
- プライバシーポリシー: https://himonavi-legal.pages.dev/privacy-policy
- 利用規約: https://himonavi-legal.pages.dev/terms
- お問い合わせ: https://himonavi-legal.pages.dev/contact
