FROM php:7.4-apache

RUN apt-get -y update \
    apt-get -y upgrade 

RUN a2enmod auth_digest auth_basic status info
RUN service apache2 restart
