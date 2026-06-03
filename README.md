# 配達売上カレンダー

Netlifyで公開する静的HTML版の配達カレンダーです。

## 重要

localStorageの保存キーは変更しません。

- `delivery_sales_calendar_data`
- `delivery_sales_calendar_settings`

この2つのキーを変えると、同じURLで使っているブラウザ内データを読めなくなる可能性があります。

## Netlify設定

- Base directory: 空欄、またはリポジトリ直下
- Build command: 空欄
- Publish directory: `.`

このフォルダ自体をGitHubリポジトリにする場合は、Netlifyは `netlify.toml` を読んでそのまま `index.html` を公開します。

