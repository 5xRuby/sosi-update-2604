---
theme: default
title: SOSI 機能アップデート
highlighter: shiki
drawings:
  persist: false
transition: slide-left
---

<div style="display:flex; flex-direction:column; align-items:center; justify-content:center; height:100%;">
  <img src="/sosi-logo.png" style="width:320px; margin-bottom:1.5rem;" />
  <h1 style="margin:0; font-size:2.5rem;">機能アップデート</h1>
  <p style="font-size:1.3rem; color:#666; margin-top:0.5rem;">2025年12月 〜 2026年4月</p>
  <p style="font-size:1rem; color:#999;">リモートアクセス管理システム 新機能のご紹介</p>
</div>

---
layout: section
---

# 📋 目次

🚀 **新機能** — 8項目

🎨 **UI/UX改善** — 1項目

🔒 **セキュリティ・管理** — 1項目

---
layout: two-cols
---

# 🌐 新機能① Telnetプロトコル対応

<br>

🌐 **4つのプロトコルに対応**
RDP、SSH、VNCに加え、Telnet接続に対応

<br>

🏭 **レガシー機器への接続**
古い機器やネットワーク機器への接続が可能に

<br>

🔐 **安全なWebアクセス**
Webブラウザ経由で安全にTelnet接続

::right::

<br>
<br>
<br>

```
Supported Protocols
├── RDP     (Windows)
├── SSH     (Linux/Unix)
├── VNC     (Cross-platform)
└── Telnet  ← NEW ✨
```

---
layout: two-cols
---

# 👁️ 新機能② リアルタイム接続モニタリング

<br>

👁️ **リアルタイム監視**
管理者がユーザーのリモート操作をリアルタイムで監視可能

<br>

📋 **コンプライアンス対応**
セキュリティ監査・コンプライアンス対応の強化

<br>

⛔ **強制切断機能**
管理者が手動で即座にリモート接続を切断可能

::right::

<br>

<video src="/videos/490-monitor-demo.webm" controls muted style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: two-cols
---

# 📁 新機能③ SFTPファイル転送記録

<br>

📁 **ファイル操作の記録**
SFTPによるアップロード・ダウンロードをすべて記録

<br>

🛡️ **アクセス制御**
ファイル転送ポリシーによるきめ細かな権限管理

<br>

✅ **監査証跡の完全性**
いつ、誰が、何を転送したかを完全に追跡

::right::

<br>

<img src="/466-file-transfer-record.png" style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: two-cols
---

# 📌 新機能④ 録画POIマーキング

<br>

📌 **重要ポイントのマーキング**
セッション録画に重要な時点をマーキング可能

<br>

🔥 **ヒートマップ表示**
操作集中箇所をヒートマップで可視化

<br>

🔍 **フィルタリング機能**
効率的な録画レビューを実現

::right::

<br>

<video src="/videos/poi-demo.webm" controls muted style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: default
---

# 🔒 新機能⑤ 暗号化録画ダウンロード

🔒 **暗号化形式** — 録画ファイルを暗号化形式でダウンロード可能

🛡️ **機密性の保護** — データの機密性を完全に保護

💻 **オフライン確認** — オフラインでの安全な録画確認が可能

<video src="/videos/527-recording-encryption.webm" controls muted style="width:80%; border-radius:8px; border:1px solid #e2e8f0; margin-top:0.5rem;" />

---
layout: two-cols
---

# 📝 新機能⑥ セッションテキスト記録

<br>

📝 **端末テキストの完全記録**
SSHセッションの端末テキストをすべて記録（Typescript）

<br>

🔎 **全文検索対応**
中国語・日本語を含むマルチ言語全文検索

<br>

📊 **監査ログとして活用**
テキストベースの監査ログとして利用可能

::right::

<br>

<video src="/videos/509-typescript.webm" controls muted style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: two-cols
---

# 🔗 新機能⑦ LDAP自動サインイン

<br>

🔗 **LDAP認証の紐づけ**
デバイスにLDAP認証を紐づけ、自動ログインが可能

<br>

⚡ **手間の削減**
ユーザーが手動で認証情報を入力する必要なし

<br>

🏢 **Active Directory統合**
Active Directory環境との統合を強化

::right::

<br>

<img src="/496-LDAP-auto-sign.png" style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: default
---

# ⚠️ 新機能⑧ ディスク容量警告

⚠️ **容量不足の警告** — システムディスクの空き容量が不足した際に警告を表示

💾 **事前検知** — 録画ファイルによるストレージ圧迫を事前に検知

📈 **安定性向上** — ディスク不足によるシステム障害を未然に防止

<img src="/disk-space-warning.png" style="width:80%; border-radius:8px; border:1px solid #e2e8f0; margin-top:0.5rem;" />

---
layout: two-cols
---

# 🎨 UI/UX改善 カスタムロゴ対応

<br>

🎨 **ブランドカスタマイズ**
システムのロゴをお客様のブランドに変更可能

<br>

⚙️ **簡単な設定**
グローバル設定から簡単にロゴを変更

<br>

🏢 **ブランディングの一貫性**
企業ブランディングの一貫性を実現

::right::

<br>

<img src="/setup-logo.png" style="width:100%; border-radius:8px; border:1px solid #e2e8f0;" />

---
layout: default
---

# 🗑️ セキュリティ 録画ファイル自動クリーンアップ

<br>

| 機能 | 説明 |
|------|------|
| 🗑️ **自動削除** | 処理済みの録画元ファイルを自動的に削除 |
| 💰 **コスト最適化** | ストレージコストの削減と最適化 |
| 🤖 **運用負担の軽減** | 管理者の手動メンテナンス負担を大幅に軽減 |

<br>

```
自動クリーンアップの流れ:

[録画完了] → [変換処理] → [変換済みファイル保存] → [元ファイル自動削除]
                                ✅ 保持              🗑️ 自動クリーン
```

---
layout: section
---

# まとめ

🌐 **接続対象の拡大** — Telnet対応でレガシー機器を含む幅広いデバイスへ

👁️ **監視・監査機能の強化** — モニタリング、Typescript、SFTP記録、POI

🔒 **セキュリティの向上** — 暗号化録画、LDAP統合、ディスク監視

⚡ **運用効率化** — 自動クリーンアップ、カスタムロゴ
