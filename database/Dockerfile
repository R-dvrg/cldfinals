FROM mariadb:latest

COPY ./mboardlogin.sql /docker-entrypoint-initdb.d

ENV MYSQL_DATABASE=mboardlogin \
    MYSQL_USER=admin \
    MYSQL_PASSWORD=FedUlQ8Hbl5KGxeF \
    MYSQL_ROOT_PASSWORD=password

EXPOSE 3306