# Women Who Go Tokyo Webpage

Women Who Go Tokyo のサイトです。Hugo + Cloudflare (Workers & Pages) で構築されています。

## ローカル開発手順

```bash
# 依存モジュール取得 (初回/更新時)
hugo mod tidy

# 開発サーバ起動
hugo server -w -D
# ブラウザ: http://localhost:1313/
```

## Firebase Hosting デプロイ

Cloudflare (Workers & Pages)でビルド・デプロイしています。

PRをマージすると本番デプロイされます。PRごとに期限付きのプレビューが作成されます。
