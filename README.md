生成して起動
```
docker-compose up -d
```

mysqlコマンドで接続
```
docker-compose exec db bash
# mysql -u root -p
```
追記：下でも可
```
docker-compose exec db mysql -u root -p
```

終了
```
docker-compose stop
```

破棄
```
docker-compose down
```
