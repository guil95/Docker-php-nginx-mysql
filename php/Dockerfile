FROM php:7.2-fpm

USER root

ADD install_dependencies.sh /install_dependencies.sh

RUN chmod +x /install_dependencies.sh

RUN cd / && ./install_dependencies.sh

RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html
