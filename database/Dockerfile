FROM postgres:alpine
EXPOSE 5432
ENV POSTGRES_PASSWORD=password
ENV POSTGRES_DB=perntodo
COPY sql_scripts /docker-entrypoint-initdb.d/
