# IG Comment Giveaway Picker
Instagramのコメント抽選を行うためのシンプルなWebツールです。

### 特徴
- CSVとしてコメントをインポート可能（[ExportComments.com](https://exportcomments.com/)の出力をサポート）。
- 当選者数を指定可能。
- 必須キーワードでフィルタリング可能。
- 暗号学的に強いシャッフルでランダム抽選。
- 当選結果をCSVとしてエクスポート可能。

### 使い方
1. [ExportComments.com](https://exportcomments.com/)からコメントをCSVでエクスポートし、`index.html`をブラウザで開く。
2. CSVファイルをアップロードし、当選者数と必要に応じてキーワードを設定。
3. **Draw**をクリックして当選者を表示し、必要なら結果をCSVでエクスポート。

### デモ
- GitHub Pagesでオンラインデモを利用できます：  
  [https://wanaincode.github.io/instagram_lottory/](https://wanaincode.github.io/instagram_lottory/)

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
1. Export comments as CSV via [ExportComments.com](https://exportcomments.com/) and open `index.html` in your browser.
2. Upload the CSV file, set the number of winners and optional keywords.
3. Click **Draw** to display winners and export results as CSV if needed.

### Demo
- Try the online demo on GitHub Pages:  
  [https://wanaincode.github.io/instagram_lottory/](https://wanaincode.github.io/instagram_lottory/)

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