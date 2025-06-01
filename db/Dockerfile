FROM postgres:15

ENV POSTGRES_USER=admin
ENV POSTGRES_PASSWORD=12345
ENV POSTGRES_DB=test_db

COPY init.sql /docker-entrypoint-initdb.d/
