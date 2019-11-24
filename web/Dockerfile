# Для начала указываем исходный образ, он будет использован как основа
FROM php:7.2-apache

RUN docker-php-ext-install \
    pdo_mysql \
    && a2enmod \
    rewrite
