FROM php:8.0-apache
RUN apt-get update && apt-get install -y iputils-ping
RUN docker-php-ext-install mysqli
COPY ./html /var/www/html
#COPY ./default.conf /etc/nginx/conf.d/default.conf
