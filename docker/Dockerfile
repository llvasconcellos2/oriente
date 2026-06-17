FROM php:5.6-apache

# Debian stretch is EOL; point apt at the archive and skip expired signing keys.
RUN sed -i -e 's|deb.debian.org|archive.debian.org|g' \
        -e 's|security.debian.org|archive.debian.org|g' /etc/apt/sources.list \
    && sed -i '/stretch-updates/d' /etc/apt/sources.list \
    && apt-get -o Acquire::Check-Valid-Until=false update -qq \
    && apt-get install -y --no-install-recommends --allow-unauthenticated \
        libpng-dev \
        libjpeg62-turbo-dev \
        libfreetype6-dev \
        libzip-dev \
    && rm -rf /var/lib/apt/lists/*

RUN docker-php-ext-configure gd --with-jpeg-dir=/usr --with-freetype-dir=/usr \
    && docker-php-ext-install -j"$(nproc)" mysql mysqli gd zip

RUN a2enmod rewrite

COPY php-overrides.ini /usr/local/etc/php/conf.d/zz-joomla-overrides.ini
