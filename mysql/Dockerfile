#BD cob base ubuntu e instalado MySQL
FROM ubuntu:latest
MAINTAINER Manuel Galvan <manugr21@gmail.com>

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y mysql-server

EXPOSE 3306

RUN service mysql start
