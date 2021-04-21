# pma-mysql8-docker

PHPMyAdminとMySQL8をDockerで動かす設定ファイル

M1 MacBookでの動作もサポート済み

## 使い方

docker-composeで起動する．

```
docker-compose up
```

データベースをインポートしたい場合は， `initdb.d/` に配置する．
