# devx-site

devx.jp のWebサイトです。Astro で作り、Cloudflare Pages で公開しています。

## 開発

```bash
npm install
npm run dev      # 開発サーバー (http://localhost:4321)
npm run build    # dist/ にビルド
npm run preview  # ビルド結果を確認
```

## デプロイ

`main` に push すると Cloudflare Pages が自動でビルド・公開します。

- ビルドコマンド: `npm run build`
- 出力ディレクトリ: `dist`
