FROM php:7.1.17-fpm

RUN docker-php-ext-install mysqli pdo pdo_mysql

COPY php.ini /usr/local/etc/php/

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/tmp \
    && mv /tmp/composer.phar /usr/local/bin/composer
