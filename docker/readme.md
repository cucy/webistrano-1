docker-webistrano
=================

## Usage

```bash
docker run --name my-webistrano --link some-mariadb:mysql -d pomu0326/webistrano
```

## Environment Variables

### `MYSQL_HOST`

MySQL Database Host's IP Address or HostName.

### `MYSQL_DATABASE`

MySQL Database Name.

### `MYSQL_USER`

MySQL User Name.

### `MYSQL_PASSWORD`

MySQL User Password.



docker run --name my-webistrano --link mysql:mysql1   -e MYSQL_HOST="172.17.0.2"  -e MYSQL_DATABASE="webistrano_production"  -e MYSQL_USER="root" -e MYSQL_PASSWORD="123456"  -p 23002:3000  -d pomu0326/webistrano 
