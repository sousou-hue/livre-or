FROM php:8.2-apache

# Installer l'extension PDO MySQL
RUN docker-php-ext-install pdo pdo_mysql

# Copier ton code PHP dans le dossier web
COPY . /var/www/html

