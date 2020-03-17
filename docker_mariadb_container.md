link https://hub.docker.com/_/mariadb

docker run --name local-mariadb -p 3306:3306 -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mariadb:tag

docker start local-mariadb
