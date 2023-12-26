
FROM php:7.4-apache

WORKDIR /var/www/html

COPY . /var/www/html

RUN docker-php-ext-install mysqli pdo pdo_mysql

EXPOSE 80

ENV DB_HOST database-1.cmlezy58ukae.us-east-1.rds.amazonaws.com
ENV DB_USER admin
ENV DB_PASSWORD goutham30
