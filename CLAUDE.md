# CLAUDE.md

## Project Overview

SOSI（Telescope）のクライアント向け機能アップデートプレゼンテーション。Slidev を使用した Web ベースのスライドデッキ。

## Tech Stack

- **Slidev** v52 — Markdown ベースのプレゼンテーションフレームワーク
- **Node.js** — mise で管理
- **pnpm** — パッケージマネージャー

## Common Commands

```bash
# 開発サーバー起動
pnpm run dev

# PDF エクスポート（要 playwright-chromium）
pnpm run export

# 静的サイトビルド
pnpm run build
```

## File Structure

- `slides.md` — 全スライドのコンテンツ（Markdown + HTML）
- `public/` — 画像・動画などの静的アセット
  - `public/videos/` — デモ動画（.webm, .mp4）
  - `public/*.png` — スクリーンショット・ロゴ

## Slide Authoring Notes

### レイアウト
- `two-cols` + `::right::` で左テキスト / 右メディアの2カラム構成
- `section` でセクション区切り
- `default` で通常スライド

### メディア埋め込み
- 動画: `<video src="/videos/xxx.webm" controls muted style="..." />`
- 画像: `<img src="/xxx.png" style="..." />`
- `public/` 直下のファイルは `/filename` で参照可能

### 言語
- スライド本文は**日本語**で記述
- SOSI = Telescope の製品名（クライアント向け名称）

## Related Repositories

- **Telescope**: https://git.5xruby.com/telescope/telescope （メイン Rails アプリ）
- **Lens**: https://git.5xruby.com/telescope/lens （リモートアクセスコンパニオン）
