# Markdown to Confluence Converter

MarkdownをConfluence Wiki Markupに変換するWebツールです。

![Screenshot](screenshot.png)

## 機能

- ✅ リアルタイム変換
- ✅ 見出し、リスト、コードブロック、テーブルなど主要な要素に対応
- ✅ ワンクリックコピー機能
- ✅ シンプルで使いやすいUI

## サポートされる変換

| Markdown | Confluence Wiki Markup |
|----------|------------------------|
| `# 見出し1` | `h1. 見出し1` |
| `## 見出し2` | `h2. 見出し2` |
| `**太字**` | `*太字*` |
| `*斜体*` | `_斜体_` |
| `- リスト` | `* リスト` |
| `1. 番号付き` | `# 番号付き` |
| ` ```code``` ` | `{code}code{code}` |
| `` `inline` `` | `{{inline}}` |
| `[text](url)` | `[text\|url]` |
| テーブル | Confluenceテーブル |

## デモ

[デモページ](https://yourusername.github.io/markdown-to-confluence/)

## ローカルで実行

```bash
# リポジトリをクローン
git clone https://github.com/yourusername/markdown-to-confluence.git
cd markdown-to-confluence

# 依存関係をインストール
npm install

# 開発サーバーを起動
npm run dev
