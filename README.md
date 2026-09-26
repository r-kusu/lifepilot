# LifePilot

LifePilot は、結婚・引越し・出産・車などの人生イベントで増える「やること」を、今日・今週・あとでの順に整理するスマホファーストのライフイベント管理アプリです。

## 現在の構成
- SEO対応ランディングページ
- PWA対応Webアプリ
- 結婚 / 引越し / 出産 / 車のイベントテンプレート
- タスク・期限・進捗管理
- 料金 / 利用規約 / プライバシーポリシー
- SEOガイド記事
- robots.txt / sitemap.xml / llms.txt
- Vercel静的デプロイ設定

## 公開手順
1. VercelでこのGitHubリポジトリをImport
2. Framework Presetは Other
3. Build Commandは空欄
4. Output Directoryは空欄（リポジトリ直下を静的配信）
5. デプロイ後、正式URLに合わせて canonical / sitemap / Supabase Auth redirect を更新

## ステータス
MVP v1。正式公開前に、事業者情報・問い合わせ先・決済・法務文面・本番ドメインを確定してください。
