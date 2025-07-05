FROM postgres:16.9-bullseye

COPY . /usr/src/db/
WORKDIR /usr/src/db/

RUN psql -U postgres -d prettynotes < setup.sql

EXPOSE 5432