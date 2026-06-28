# SmartRC 2026-06-28 Preview

2026-06-28分だけを確認するための静的プレビューページです。

- 公開ページ本体: `index.html`
- 本番公開URL: https://poq-preview-webpage.vercel.app/
- GitHub Pages副経路: https://rs517.github.io/poq-preview-webpage/
- サーバー処理なし
- SmartRCへのリアルタイムアクセスなし
- CSV内容はHTML内のJSONとして埋め込み
- 取得件数: 全3開催・36R・463頭

## Deployment

このrepositoryの `main` branchへpushすると、Vercelが静的HTMLを公開します。GitHub Pagesも `main` branch / root で有効化されていますが、共有URLはVercelを正とします。

## ローカル確認

```bash
python3 -m http.server 8080
```

ブラウザで `http://127.0.0.1:8080` を開きます。
