# zenn-content

[Zenn](https://zenn.dev) の記事を管理するリポジトリ。GitHub 連携で push すると Zenn に公開される。

## 構成

- `articles/*.md` — 各記事。frontmatter の `published` を `true` にすると公開される。

## ローカルプレビュー

```bash
npm install
npm run preview   # http://localhost:8000
```

## 新規記事

```bash
npm run new:article
```
