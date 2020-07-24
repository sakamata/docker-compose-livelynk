# Livelynk Docker-compose 環境レポジトリ

## 構成

- php 7.4-fpm
- nginx 1.15.6
- mysql 8.0
- laravel 5.6.39(別レポジトリ)

livelynk アプリ本体(Laravel)は本リポジトリと同じ階層に app フォルダを設置、配下に livelynk レポジトリを設置する

```
├docker-compose-livelynk
└app
  └livelynk
```
