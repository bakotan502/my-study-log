# かんたん日記

このリポジトリは、`gigaschool/tiny-diary` をベースにしたシンプルな日記アプリです。

日付、今日の気分、ひとことメモを入力して保存できる静的サイトで、ブラウザの `localStorage` に記録が残ります。保存後は過去ログの一覧表示、検索、編集、削除、気分フィルタ、気分バイオリズムの表示まで行えます。

## 主な機能

- 日付入力と自動日付補完
- 5段階の気分選択
- 一言メモの保存
- 過去ログの一覧表示
- 記録の編集と削除
- メモテキスト検索
- 気分フィルター
- 最近の気分変化をSVGで可視化するバイオリズム表示

## 技術スタック

- HTML
- CSS
- JavaScript
- localStorage

## 起動方法

ビルドツールや依存パッケージは不要です。

1. このリポジトリをクローンまたはダウンロード
2. `index.html` をブラウザで開く
3. 日記を入力して保存する

```bash
python3 -m http.server 8000
```

その後、ブラウザで `http://localhost:8000` を開いて利用できます。

## プロジェクト構成

```text
.
├── index.html
├── styles.css
├── app.js
├── README.md
├── LICENSE
├── image.png
├── .gitignore
└── .github/
```

## データ保存

アプリは `tiny-diary.entries.v1` というキーで `localStorage` に記録を保存します。

## ライセンス

MIT License
