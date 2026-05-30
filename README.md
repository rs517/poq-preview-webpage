# SmartRC 2026-05-31 Preview

2026-05-31分だけを確認するための静的プレビューページです。

- 公開ページ本体: `index.html`
- サーバー処理なし
- SmartRCへのリアルタイムアクセスなし
- CSV内容はHTML内のJSONとして埋め込み
- 取得件数: 全2開催・24R・348頭
- ML予測付与: あり（314頭 / 348頭）

## GitHub Pages

このrepositoryのGitHub Pagesを `main` branch / root で有効化すると、`index.html` がそのまま公開されます。

## ローカル確認

```bash
python3 -m http.server 8080
```

ブラウザで `http://127.0.0.1:8080` を開きます。
