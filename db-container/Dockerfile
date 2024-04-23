FROM postgres:latest

ARG POSTGRES_PASSWORD 
ENV POSTGRES_PASSWORD=$POSTGRES_PASSWORD 
ENV POSTGRES_DB=my_database

#copy initialization script for custom setup
COPY init.sql /docker-entrypoint-initdb.d/
