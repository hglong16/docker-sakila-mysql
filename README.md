## This repo run instance mysql with sakila-sample-database

Base on [https://github.com/sakiladb/mysql](https://github.com/sakiladb/mysql)

By default these are created:

- database: sakila
- username / password: sakila / p_ssW0rd
## Start
```
docker compose up -d
docker exec -it sakiladb-mysql mysql --host=localhost --port=3306 --user=sakila --password=p_ssW0rd sakila
```
