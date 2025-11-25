# Markdown to Confluence Converter

Markdownファイルを Confluence 記法に変換するWebツールです。

## 機能

- ✏️ テキスト入力モード：Markdownを直接入力
- 📁 ファイルアップロードモード：複数の.mdファイルを一括変換
- 📄 ソースモード：Confluence記法をコピー可能
- 👁 プレビューモード：変換結果をプレビュー表示
- 💾 一括ダウンロード：全ファイルを変換してダウンロード

## 使い方

### オンラインで使用
GitHub Pagesでホスティングされているバージョンを使用:
https://[your-username].github.io/markdown-to-confluence/

### ローカルで使用

1. リポジトリをクローン:
```bash
git clone https://github.com/[your-username]/markdown-to-confluence.git
cd markdown-to-confluence
```

2. ブラウザで開く:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

または、index.htmlをブラウザにドラッグ&ドロップしてください。

### Confluenceへの埋め込み

1. Confluenceページを編集モードで開く
2. `/` を入力してマクロメニューを開く
3. `HTML` マクロを選択
4. `index.html` の内容をコピー&ペースト
5. 保存

## 対応している変換

- 見出し（h1〜h6）
- 太字・斜体・打ち消し線
- 箇条書きリスト・番号付きリスト
- コードブロック・インラインコード
- リンク・画像
- 引用
- 水平線
- テーブル

## 技術スタック

- React 18.2.0
- Vanilla JavaScript（CDN経由）
- HTML5 / CSS3

## ライセンス

MIT License

## 貢献

プルリクエスト歓迎です！バグ報告や機能リクエストはIssueでお願いします。
