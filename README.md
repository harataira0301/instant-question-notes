# Instant Question Notes

Codex と育てる質問ノート集です。

Codex に「質問: ...」と投げた内容を、静的 HTML のノートとして蓄積するための最小構成です。技術だけでなく、料理、植物、生活知識、制度、買い物の調査など、あとで読み返したい疑問を1テーマ1ページで残します。

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

## Topic Examples

- `hardware/`, `ai/`, `web/`: 技術・開発・電子工作。
- `cooking/`: レシピ、保存、食材、調理のコツ。
- `plants/` or `nature/`: 身近な花、野草、季節の観察。
- `life/`: 暮らし、健康まわりの一般知識、手続き。
- `compliance/`: 規制、制度、実務上の確認事項。

## GitHub Pages

GitHub の repository settings で Pages の source を `GitHub Actions` に設定してください。
