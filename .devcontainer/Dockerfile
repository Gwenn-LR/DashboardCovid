# syntax = docker/dockerfile:1

FROM mysql

WORKDIR /app

COPY . .

CMD mysql -h database -u root -p < data/vaccination.sql