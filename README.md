# 概要
Apache+PHP+PostgreSQLのDocker

友人の学習用に作成したため雑です

# 使用方法
1. `docker network create sample-backend`を実行
1. `docker-compose up -d --build`を実行
1. `docker exec -it phpgres-sample-db pg_restore -U user -d sample /docker-entrypoint-initdb.d/dvdrental.tar`を実行

以下で起動していることを確認
http://localhost:8080
