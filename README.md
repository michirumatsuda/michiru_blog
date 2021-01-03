# DB設計

## form テーブル

makers

| カラム名 | 型 | 説明 |
| --- | --- | --- |
| company_name | text | `企業名(お名前)` |
| tel | integer | `電話番号` |
| email | text | `メールアドレス` |
| user_name | text | `ご担当社様氏名` |
| business_field_other | text | `その他の事業分野の場合自由入力` |


business_genre

| カラム名 | 型 | 説明 |
| --- | --- | --- |
| id | integer | `番号` |
| name | text | `名前` |