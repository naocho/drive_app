# テーブル設計

## member テーブル

| Column        | Type   | Options     |
| --------------| ------ | ----------- |
| name          | string | null: false |
| kana_name     | string | null: false |
| email         | string | null: false |
| phone_numder  | string | null: false |
| address       | string | null: false |
| license table | string | null: false |
| license back  | string | null: false |


## contact テーブル

| Column        | Type       | Options                        |
| ------------- | ---------- | ------------------------------ |
| name          | references | null: false, foreign_key: true |
| address       | string     | null: false                    |
| subject       | integer    | null: false                    |
| message       | string     | null: false                    |


## parttime テーブル

| Column        | Type       | Options                        |
| ------------- | ---------- | ------------------------------ |
| name          | string     | null: false                    |
| age           | string     | null: false                    |
| phone_numder  | string     | null: false                    |
| email         | string     | null: false                    |
| license table | string     | null: false                    |
| license back  | string     | null: false                    |
| Checklist | string         | null: false                    |
| message       | string     | null: false                    |





