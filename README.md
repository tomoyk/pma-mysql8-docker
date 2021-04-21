# pma-mysql8-docker

PHPMyAdminとMySQL8をDockerで動かす設定ファイル

M1 MacBookでの動作もサポート済み

## 使い方

(1) データベースをインポートしたい場合は， `initdb.d/` に配置する．

(2) docker-composeで起動する．

```
docker-compose up
```

(3) PHPMyAdminに `http://localhost:8080` からアクセスする．
