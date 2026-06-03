# 配達売上カレンダー

Netlifyで公開する静的HTML版の配達カレンダーです。

## 重要

localStorageの保存キーは変更しません。

- `delivery_sales_calendar_data`
- `delivery_sales_calendar_settings`

この2つのキーを変えると、同じURLで使っているブラウザ内データを読めなくなる可能性があります。

## GitHub Pages設定

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

`index.html` をリポジトリ直下に置いているため、ビルドなしでそのまま公開できます。
