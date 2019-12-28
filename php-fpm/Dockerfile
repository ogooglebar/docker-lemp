FROM php:7.3-fpm-alpine

# Dependencies
RUN apk --no-cache --update add curl nano \
    libpng-dev \
    libzip-dev \
    zlib-dev \
    unzip \
    zip \
    git

# Extensions
RUN docker-php-ext-install pdo pdo_mysql mysqli mbstring zip exif gd