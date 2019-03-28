FROM php:7.2-fpm-alpine3.8

USER root

ADD install_dependencies.sh /install_dependencies.sh

RUN chmod +x /install_dependencies.sh

RUN cd / && ./install_dependencies.sh

WORKDIR /var/www/html
