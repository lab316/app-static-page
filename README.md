# App Static Page Generator

クエリパラメータで必要な値を渡すだけでアプリに必要な静的ページが生成される、汎用的なジェネレータです。

## ページ一覧
|ページ名|URL|パラメータ|
|---|---|---|
|汎用的な利用規約|`/gp.html`|`company`|
|キャンペーン応募要項用の利用規約|`/campaign.html`|`company`,`capmaign`|
|オンラインショップ用の利用規約|`/onlineshop.html`|`company`|
|掲示版・SNS系向きの利用規約|`/sns.html`|`company`|
|プライバシーポリシー|`/privacy.html`|`company`,`address`,`department`,`email`|
|採用活動用：応募者の個人情報に関する取扱い方針|`/recruit.html`|`company`,`contact`,`address`|

## 謝辞
https://kiyaku.jp/index.html