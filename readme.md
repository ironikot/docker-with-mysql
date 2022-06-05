# About
M1 Macの環境で、DockerでDBを作り、外部から接続してみるものです。
mysqlを試しに使っています。

# How to use
1. db_testのディレクトリに移動します.
2. 起動コマンドを叩く


```sh
docker-compose up -d 
```

3. mysqlにログインしてみる。

この時、hostはLocalhostと記述するとNGっぽいです。
```
mysql --host=127.0.0.1 --user=root --password=password --port=3306
```

