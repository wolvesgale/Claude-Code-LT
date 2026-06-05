# デモ用プロンプト

当日 claude.ai に貼り付けて実行 → 生成された HTML を `first-step.html` として保存 → git push → 参加者に URL シェア

---

```
あなたはWebデザイナー兼エンジニアです。

「やさしいLT大会『Claude Code 編』#1」の参加者向け
Claude Code 第一歩ガイドのランディングページを1ファイルのHTMLで作ってください。

【参加者像】
- Claude Code でつくってみた人
- ここが難しかった・詰まった人
- こんなことできた！という体験をした人
- Codex や Antigravity など他ツールと比べたい人
- エンジニアではない現場の人（営業・製造・医療・事務など）

【ページ構成】
1. ヒーロー：「あなたの言葉が、コードになる。」
2. 参加者4タイプ別カード（つくった / 難しかった / できた / 他ツール派）
3. 壁の乗り越え方3つ
4. 今日から使えるプロンプト例（コピーボタン付き）
5. CTA：「claude.ai/code で始める」

【デザイン】
- 1ファイルHTML完結（CSS・JS込み）
- ダークテーマ・星空背景・Claudeオレンジ（#d97757）アクセント
- スクロールフェードイン・スマホ対応・絵文字でビジュアルリッチに

ファイル名は first-step.html で保存してください。
```

---

## デプロイ（生成後 30 秒）

```bash
git add first-step.html
git commit -m "add first step lp"
git push origin main
```

→ `https://claude-code-lt.vercel.app/first-step.html` を参加者にシェア
