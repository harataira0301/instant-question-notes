# Instant Question Notes

Codex と育てる技術ノートです。

Codex に「質問: ...」と投げた内容を、静的 HTML の技術ノートとして蓄積するための最小構成です。

## Structure

```text
.
├── .github/workflows/static.yml
├── styles/site.css
├── images/
├── examples/
├── AGENTS.md
├── README.md
└── index.html
```

## Workflow

1. スマホやPCから Codex に `質問: ...` と依頼する。
2. Codex が `examples/` などのカテゴリ配下に HTML ページを追加する。
3. `index.html` に新しいノートへのリンクを追加する。
4. 差分を確認してから commit / push する。
5. GitHub Pages で公開する。

## GitHub Pages

GitHub の repository settings で Pages の source を `GitHub Actions` に設定してください。
