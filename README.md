# SOSI 機能アップデート プレゼンテーション

SOSI（Telescope）リモートアクセス管理システムの機能アップデート紹介スライド（2025年12月〜2026年4月）。

[Slidev](https://sli.dev) で構築されたWebベースのプレゼンテーションです。

## セットアップ

```bash
pnpm install
```

## 使い方

### 開発サーバー（プレゼンテーション）

```bash
pnpm run dev
```

ブラウザで http://localhost:3030 を開きます。

- ← → キーでスライドを切り替え
- `/overview` で全スライド一覧
- `/presenter` でプレゼンターモード

### PDF エクスポート

```bash
pnpm add -D playwright-chromium
pnpm run export
```

### 静的サイトビルド

```bash
pnpm run build
```

`dist/` ディレクトリに生成されます。任意の HTTP サーバーでホスティング可能。

## スライド構成

| # | タイトル | メディア |
|---|---------|---------|
| 1 | タイトル（SOSI ロゴ） | — |
| 2 | 目次 | — |
| 3 | Telnetプロトコル対応 | — |
| 4 | リアルタイム接続モニタリング | 🎬 動画 |
| 5 | SFTPファイル転送記録 | 🖼️ スクリーンショット |
| 6 | 録画POIマーキング | 🎬 動画 |
| 7 | 暗号化録画ダウンロード | 🎬 動画 |
| 8 | セッションテキスト記録 | 🎬 動画 |
| 9 | LDAP自動サインイン | 🖼️ スクリーンショット |
| 10 | ディスク容量警告 | 🖼️ スクリーンショット |
| 11 | カスタムロゴ対応 | 🖼️ スクリーンショット |
| 12 | 録画ファイル自動クリーンアップ | — |
| 13 | まとめ | — |

## ディレクトリ構成

```
.
├── slides.md              # スライド本体
├── public/                # 静的アセット
│   ├── sosi-logo.png
│   ├── 466-file-transfer-record.png
│   ├── 496-LDAP-auto-sign.png
│   ├── disk-space-warning.png
│   ├── setup-logo.png
│   └── videos/
│       ├── 490-monitor-demo.webm
│       ├── 509-typescript.webm
│       ├── 527-recording-encryption.webm
│       └── poi-demo.webm
├── package.json
└── README.md
```
