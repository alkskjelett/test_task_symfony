FROM php:8.2-fpm

#RUN apt-get update && apt-get install php8.2-pgsql \
#    && docker-php-ext-install pdo_pgsql

COPY ../ ./var/www/html

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer