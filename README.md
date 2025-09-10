# IG Comment Giveaway Picker
Instagramのコメント抽選を行うためのシンプルなWebツールです。

### 特徴
- CSVとしてコメントをインポート可能（[ExportComments.com](https://exportcomments.com/)の出力をサポート）。
- 当選者数を指定可能。
- 必須キーワードでフィルタリング可能。
- 暗号学的に強いシャッフルでランダム抽選。
- 当選結果をCSVとしてエクスポート可能。

### 使い方
1. 準備: [ExportComments.com](https://exportcomments.com/)からInstagramコメントをCSVでエクスポート。
2. `index.html`をブラウザで開く（サーバーやAPI不要）。
3. CSVファイルをアップロード。
4. 当選者数と（必要であれば）必須キーワードを設定。
5. **Draw**をクリックすると当選者が表示されます。
6. （必要なら）結果をCSVとしてエクスポート。

### デプロイ
- このリポジトリをGitHubにPushし、**GitHub Pages**を有効にするとオンラインで共有可能。
- 完全にフロントエンドのツールなので、バックエンドは不要です。

### フォルダ構成
このリポジトリのフォルダ構成は以下の通りです：

```
instagram_lottory/
├── index.html          # メインのHTMLファイル
├── README.md           # この説明ファイル
├── LICENSE             # ライセンス情報
├── .gitignore          # Git管理除外ファイル指定
└── sample/
    └── comments.csv    # サンプルのInstagramコメントCSVファイル
```

---

## English Version

A simple web-based tool to run Instagram comment giveaways.

### Features
- Import comments as CSV (supports [ExportComments.com](https://exportcomments.com/) output).
- Specify number of winners.
- Optional required keywords filter.
- Random drawing with cryptographically strong shuffle.
- Export the winners list as CSV.

### How to Use
1. Prepare: Export Instagram comments as CSV via [ExportComments.com](https://exportcomments.com/).
2. Open `index.html` in your browser (no server or API needed).
3. Upload the CSV file.
4. Set the number of winners and (optionally) required keywords.
5. Click **Draw** to see winners.
6. (Optional) Export results as CSV.

### Deployment
- Push this repo to GitHub and enable **GitHub Pages** to share online.
- Because it is a pure front-end tool, no backend is required.

### Folder Structure
The repository folder structure is as follows:

```
instagram_lottory/
├── index.html          # Main HTML file
├── README.md           # This documentation file
├── LICENSE             # License information
├── .gitignore          # Git ignore file
└── sample/
    └── comments.csv    # Sample Instagram comments CSV file
```