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
 #docker起動 <br>
 $ docker-compose up -d --build <br><br>
 
 #phpのコンテナに入る <br>
 $ docker exec -it php.7.3 bash <br><br>

 #laravelプロジェクト作成 <br>
 $ laravel new [project name]
```
