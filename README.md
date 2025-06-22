# 郵便番号検索アプリ

## 概要
PythonのTkinterで作成したシンプルな郵便番号検索アプリです。  
入力した7桁の郵便番号を使って、[ZipCloud](https://zipcloud.ibsnet.co.jp/)のAPIから住所情報を取得して表示します。

## 必要環境
- Python 3.x（推奨バージョン 3.7以上）
- requests ライブラリ
- tkinter（Python標準ライブラリに含まれています）

## インストール方法

1. リポジトリをクローンします。

```bash
git clone https://github.com/mitsu-nabe/zip.app.py.git
cd zip.app.py
```

## 依存パッケージをインストール
```bash
pip install requests
```

## 使い方
```bash
python zip.app.py
```
- 起動後、郵便番号を7桁入力すると自動で「検索」ボタンが有効になります。
- 「検索」ボタンを押すと住所が表示されます。
- 郵便番号が7桁以外の場合や無効な番号の場合は検索できません。

## 注意事項
- インターネット接続が必要です。
- ZipCloud APIの利用制限に注意してください。

## ライセンス
MIT License

## 作者
mitsu-nabe

## お問合せ
handlove55@gmail.com