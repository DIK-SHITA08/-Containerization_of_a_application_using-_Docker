FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Dikshita"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYDQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
