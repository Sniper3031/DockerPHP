FROM php:7.3-apache
RUN docker-php-ext-install mysqli

ADD ./bookmedik /var/www//html/bookmedik

CMD /usr/sbin/apache2ctl -D FOREGROUND
