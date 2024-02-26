FROM mysql:8.0.33
LABEL "Project"="TENSHI"
LABEL "Author"="lain"

ENV MYSQL_ROOT_PASSWORD="lain"
ENV MYSQL_DATABASE="Angels"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql