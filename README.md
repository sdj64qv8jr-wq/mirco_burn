# 🔥 MIRCO BURN

**MIRCO Token Incinerator — Solana SPL Token Burn Page**

## Deploy to GitHub Pages

1. このリポジトリを GitHub にプッシュ
2. Settings → Pages → Branch: `main` / `root` を選択
3. 数分後に `https://<username>.github.io/<repo>/` で公開

## 使い方

1. **STEP 01** — Solana ウォレットアドレスを入力して SCAN
2. **STEP 02** — バーンしたい量を選択（25% / 50% / 75% / ALL）
3. **STEP 03** — BURN IT ボタン → Phantom/Solflare で署名

## Contract Address

`HGNjaczVcV6tKbpWCLarszbwtwB9hUd2Cd7ySbabpump`

## ファイル構成

```
index.html      # メインページ
assets/
  bg.jpg        # 背景画像
  coin.png      # MIRCOコインロゴ
.nojekyll       # GitHub Pages用
README.md
```

## Tech

- Solana Web3.js v1.87.6
- SPL Token Program (burn opcode: 0x08)
- No backend — 完全クライアントサイド
- Phantom / Solflare 対応
