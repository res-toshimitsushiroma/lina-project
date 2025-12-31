# 🌸 LINA - LINE Integrated Appointment System

<div align="center">
  
  ![LINA Logo](https://img.shields.io/badge/LINA-v1.0-d4a574?style=for-the-badge&logo=line&logoColor=white)
  ![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)
  ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
  
  **美容サロンのための次世代予約管理システム**
  
  [デモを見る](https://yourusername.github.io/lina-project/demo/) | [ドキュメント](docs/) | [計画書](docs/lina-project-plan.html)
  
</div>

---

## 📌 概要

LINA（リナ）は、LINEとGoogleを完全統合した革新的な予約管理システムです。美容サロンのオーナー様とお客様の両方に最高の体験を提供します。

### ✨ 特徴

- 🆓 **永久無料プラン** - 小規模サロンでも導入可能
- 📱 **LINE完全統合** - お客様の使い慣れたツールで予約
- 📅 **Googleカレンダー連携** - スケジュール管理を一元化
- 🔒 **法的完全防御** - 利用規約の全文保存システム
- 📊 **詳細な分析** - 売上・顧客分析レポート

## 🚀 デモ

### オンラインデモ
- [🏠 紹介サイト](https://yourusername.github.io/lina-project/)
- [🎯 デモ選択画面](https://yourusername.github.io/lina-project/demo/)
- [👔 オーナー向け初期設定](https://yourusername.github.io/lina-project/demo/lina-owner-setup.html)
- [📊 管理画面](https://yourusername.github.io/lina-project/demo/lina-owner-admin.html)
- [📱 顧客予約画面](https://yourusername.github.io/lina-project/demo/lina-customer.html)

### 管理機能デモ
- [📝 利用規約設定](https://yourusername.github.io/lina-project/src/mockups/lina-terms-settings.html)
- [👤 顧客詳細（履歴付き）](https://yourusername.github.io/lina-project/src/mockups/lina-customer-detail-with-terms.html)
- [💊 施術記録（証跡付き）](https://yourusername.github.io/lina-project/src/mockups/lina-treatment-record-with-terms.html)

## 📂 プロジェクト構成

```
lina-project/
├── index.html              # 紹介サイトトップ
├── README.md              # このファイル
├── LICENSE                # MITライセンス
│
├── demo/                  # デモファイル
│   ├── demo-index.html    # デモ選択画面
│   ├── lina-owner-setup.html    # 初期設定
│   ├── lina-owner-admin.html    # 管理画面
│   └── lina-customer.html       # 予約画面
│
├── docs/                  # ドキュメント
│   └── lina-project-plan.html   # プロジェクト計画書
│
└── src/                   # ソースファイル
    ├── mockups/          # モックアップ
    │   ├── lina-terms-settings.html
    │   ├── lina-customer-detail-with-terms.html
    │   └── lina-treatment-record-with-terms.html
    └── specifications/   # 仕様書
        └── lina-terms-fulltext-storage.html
```

## 💻 技術スタック

### フロントエンド
- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** Custom Components

### バックエンド
- **Framework:** Laravel 10
- **Language:** PHP 8.2
- **Database:** PostgreSQL 15
- **Cache:** Redis

### インフラ
- **Hosting:** Google Cloud Run
- **Storage:** Google Cloud Storage
- **CDN:** Cloudflare
- **Monitoring:** Google Cloud Monitoring

### 外部連携
- **LINE:** Messaging API
- **Google:** Calendar API, Sheets API
- **Auth:** Firebase Authentication

## 🔧 セットアップ

### 前提条件
- Node.js 18+
- PHP 8.2+
- PostgreSQL 15+
- LINE Developers アカウント
- Google Cloud Platform アカウント

### インストール手順

```bash
# リポジトリのクローン
git clone https://github.com/yourusername/lina-project.git
cd lina-project

# デモの確認（ローカル）
# 任意のHTTPサーバーで実行
python -m http.server 8000
# ブラウザで http://localhost:8000 を開く
```

## 📋 機能一覧

### コア機能
- ✅ LINE経由の予約受付
- ✅ Googleカレンダー同期
- ✅ 顧客管理（CRM）
- ✅ 施術記録管理
- ✅ 利用規約管理（全文保存）

### 管理機能
- ✅ ダッシュボード
- ✅ 売上分析
- ✅ 顧客分析
- ✅ スタッフ管理
- ✅ メニュー管理

### セキュリティ
- ✅ 多要素認証
- ✅ データ暗号化
- ✅ 監査ログ
- ✅ GDPR対応

## 🗓️ ロードマップ

### Phase 1: MVP (2025 Q1)
- [x] プロジェクト設計
- [x] モックアップ作成
- [ ] 基盤開発
- [ ] LINE API統合

### Phase 2: Beta (2025 Q2)
- [ ] Google API統合
- [ ] 利用規約システム
- [ ] 管理画面実装
- [ ] ベータテスト

### Phase 3: Release (2025 Q3)
- [ ] 本番環境構築
- [ ] セキュリティ監査
- [ ] 正式リリース
- [ ] マーケティング開始

### Phase 4: Growth (2025 Q4)
- [ ] 機能拡張
- [ ] 多言語対応
- [ ] AI機能追加
- [ ] 全国展開

## 💰 料金プラン

| プラン | 月額 | 予約数/日 | 主な機能 |
|--------|------|-----------|----------|
| **Free** | ¥0 | 3件まで | 基本機能すべて |
| **Basic** | ¥2,980 | 10件まで | + 分析機能 |
| **Pro** | ¥9,800 | 無制限 | + API連携・カスタマイズ |
| **Enterprise** | お問い合わせ | 無制限 | + 専用サポート |

## 🤝 貢献

プロジェクトへの貢献を歓迎します！

1. このリポジトリをフォーク
2. 機能ブランチを作成 (`git checkout -b feature/AmazingFeature`)
3. 変更をコミット (`git commit -m 'Add some AmazingFeature'`)
4. ブランチにプッシュ (`git push origin feature/AmazingFeature`)
5. プルリクエストを作成

## 📝 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 📧 お問い合わせ

- **会社:** 合同会社RES
- **メール:** info@res-company.jp
- **ウェブサイト:** https://res-company.jp
- **住所:** 沖縄県南城市

## 🙏 謝辞

- LINE Developers
- Google Cloud Platform
- すべてのコントリビューター
- 美容サロンオーナーの皆様

---

<div align="center">
  
  **Made with ❤️ in Okinawa**
  
  Copyright © 2024 合同会社RES. All rights reserved.
  
</div>
