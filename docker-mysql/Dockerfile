# FROM mysql:latest
FROM mysql:8-debian

# MySQLの署名切れによる問題の解消
RUN rm /etc/apt/sources.list.d/mysql.list

RUN apt-get update && apt-get install -y \
    vim \
    unzip
