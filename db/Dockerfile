FROM postgres:13.5-alpine3.14

COPY create-multiple-postgresql-databases.sh /docker-entrypoint-initdb.d/create-multiple-postgresql-databases.sh

CMD ["docker-entrypoint.sh", "postgres"]