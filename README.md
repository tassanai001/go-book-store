# start MySQL Docker
docker run --name mysql-book-store -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 -d mysql:latest