# SYNTHESIS — AI統合提案エンジン

複数メンバーの意見を5つのAIエージェントが統合し、役員向け提案書を自動生成するWebアプリです。

## 🚀 デモ

**[→ アプリを開く](https://your-username.github.io/synthesis/)**

## ✨ 機能

- **5エージェント統合** — 問題抽出・止揚分析・戦略統合・スライド設計・役員レビュー
- **プロセス改革図** — AS-IS / TO-BE フロー図を自動生成（引き出し線コメント付き）
- **SVG図解** — 戦略マップ・ロードマップ・ステークホルダーマップ・因果連鎖グラフ
- **PDF出力** — HTMLダウンロード → ブラウザ印刷でPDF化
- **9名以上対応** — 大規模チームの意見を一括統合

## 🔑 必要なもの

- [Anthropic APIキー](https://console.anthropic.com)（Claude Sonnet 4.6使用）
- モダンブラウザ（Chrome / Edge / Safari）

APIキーはブラウザのsessionStorageのみに保存され、外部サーバーには送信されません。

## 📦 セットアップ（GitHub Pages）

```bash
# 1. このリポジトリをfork または clone
git clone https://github.com/your-username/synthesis.git
cd synthesis

# 2. そのままGitHub Pagesで公開
# Settings → Pages → Source: main branch / root
```

**index.html 1ファイルのみ** で動作します。ビルド不要。

## 🏢 社内サーバーでの利用

APIキーを環境変数で管理したい場合は、`server/` フォルダのNode.jsサーバー版をご利用ください（要: Node.js 18+）。

## ⚠️ 注意事項

- APIキーはブラウザセッション中のみ保持されます（タブを閉じると削除）
- Anthropic APIの利用料金が発生します（Claude Sonnet 4.6）
- 大規模利用の場合はレート制限にご注意ください

## 📄 ライセンス

MIT
