```bash
# Dockerコンテナを起動
docker-compose up -d

# ログイン
mysql -u root -p -h localhost -P 3306 --protocol=tcp

# DB一覧
show databases;

# Table一覧
show tables;

# フィールド一覧
show fields from テーブル名

# テーブルの中身を確認
use db名
select * from table名

# SQLファイル実行
\. /Users/idoharumare/private/tech_upbringing_2021_db/docker/schemas/sample.sql

