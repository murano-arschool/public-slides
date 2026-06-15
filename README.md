# public-slides

GitHub Pages で公開しているスライド置き場です。スライドは依存・ビルド不要の **単一HTMLファイル**。

## 公開サイト

- 一覧: https://murano-arschool.github.io/public-slides/
- バイブコーディングで、子どもの学びはどう変わるのか（コエテコEXPO 2026）:
  https://murano-arschool.github.io/public-slides/coeteco20260615/

## 構成

```
docs/                        ← GitHub Pages の公開ディレクトリ（main / docs）
├── index.html               ← デッキ一覧
└── coeteco20260615/
    └── index.html           ← スライド本体
```

## ローカルで見る

```bash
cd docs
python3 -m http.server 8000
# → http://localhost:8000/
```

操作：`→ / Space`＝次へ、`←`＝戻る、`click`＝追加表示。
