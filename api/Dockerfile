FROM php:8.2-apache
COPY fail.php /var/www/html/.
COPY success.php /var/www/html/.
#RUN a2enmod deflate expires rewrite

EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]

