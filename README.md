# PHP Docker 環境

PHP モジュールモード

## 使用手順

- 1 `docker compose build`
- 2 `docker compose up -d`

_web サイトは`http://localhost:8080`_  
_phpmyadmin は`http://localhost:8000`_

## MYSQL 環境変数

```md
MYSQL_ROOT_PASSWORD: root
MYSQL_DATABASE: test
MYSQL_USER: test
MYSQL_PASSWORD: test
```

## 注意点

本番環境運用時は環境変数を`.env`ファイルに隠蔽してください
