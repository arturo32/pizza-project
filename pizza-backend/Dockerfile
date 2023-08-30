FROM postgres:15.2-alpine as db-img-mvc

COPY create_pizza_db.sql /docker-entrypoint-initdb.d/create_pizza_db.sql

ENV PGDATA=/data
ENV POSTGRES_PASSWORD=postgres
