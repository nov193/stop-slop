# Stop Slop 日本語版

[hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) の日本語版と、見た目への拡張。

## 中身

```
ja/
├── SKILL.md              # 日本語の文章ルール
├── references/
│   ├── phrases.md        # 削る言い回し
│   ├── structures.md     # 避ける構文
│   └── examples.md       # 書き換え例
└── design/
    ├── SKILL.md          # 見た目のルール（原典に無い拡張）
    └── slides.md         # Claude Design のスライドへの組み込み方
```

## 原典との違い

- 直訳ではない。「〜と言えるでしょう」の逃げ、過剰な敬語、ビジネス定型句（解像度、刺さる）など、日本語で出やすい癖に置き換えた。
- `design/` は原典に無い。文章のルールを、スライドやページの見た目に当てはめた。

## 使い方

- **Claude Code / Obsidian vault:** `ja/` を `.claude/skills/stop-slop-ja/` に、`ja/design/` を `.claude/skills/stop-slop-design/` に置く。
- **Claude Projects:** `ja/SKILL.md` と `references/` をプロジェクトナレッジに入れる。

## ライセンス

MIT（原典に準ずる）
