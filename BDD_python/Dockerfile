FROM mysql

ENV MYSQL_DATABASE=mysqlsampledatabase \
    MYSQL_ROOT_PASSWORD=root_password

ADD bdd/bdd.sql /docker-entrypoint-initdb.d

EXPOSE 3306
