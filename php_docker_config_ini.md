Создать директорию docker/php-fpm/conf.d
Добавить нужные конфиги 
Добавить в php dockerfile команду
COPY docker/php/conf.d/opcache.ini /usr/local/etc/php/conf.d/opcache.ini
