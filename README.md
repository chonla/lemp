# LEMP Stack

Linux, Nginx, MariaDB, and PHP environment stack.

## Setup

```
docker-compose up -d
```

## What this stack provides?

* `html` folder contains root of application.
* default port for web is `8080`.
* default port for database (mariadb) is `3306`.
* Database is initializable like creating tables or adding default data to database by editing migration script to `./docker/mariadb/migration.sql`.