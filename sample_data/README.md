# サンプルデータ（すべて架空）

実在の顧客・取引先・作品ではありません。Google Sheets に「ファイル → インポート」で取り込んで画面イメージを確認できます。
列名は docs/11_データ辞書.md のキー名に対応しています。

| ファイル | テーブル | 設計書 |
|---|---|---|
| artworks.csv | 作品台帳 | 02 |
| products.csv | 商品マスタ | 02 |
| parties.csv | 取引先 | 03 |
| contacts.csv | 担当者 | 03 |
| sales.csv | 売上台帳 | 04 |
| expenses.csv | 経費台帳 | 04 |
| fx_rates.csv | 為替レート（※架空の値） | 04 |
| locations.csv | 拠点マスタ | 05 |
| stock_movements.csv | 入出庫履歴 | 05 |
| consignments.csv | 委託契約 | 05 |
| deals.csv | 海外営業パイプライン | 06 |
| events.csv | 展示・イベント | 02/05 |

**注意**：sales.csv の `unit_price` / `amount_jpy` は **税抜** です（商品マスタの価格は税込。例：3,850円(税込) ÷ 1.1 = 3,500円）。
為替レートはサンプル用の架空値です。
