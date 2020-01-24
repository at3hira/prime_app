# prime_app

# 環境構成
　•　OS Debian 10.2
　•　PHP 7.3.13-fpm
　•　nginx 1.17.6
　•　mysql 5.7
　•　redis 5.0.7
<br>
<br>
### laravelプロジェクト立ち上げまで
```
 #docker起動
 $ docker-compose up -d --build
 
 #phpのコンテナに入る
 $ docker exec -it php.7.3 bash

 #laravelプロジェクト作成
 $ laravel new [project name]
```
