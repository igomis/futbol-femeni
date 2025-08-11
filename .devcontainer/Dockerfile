FROM mcr.microsoft.com/devcontainers/php:8.2

# Node 20 per a Vite 7 / laravel-vite-plugin 2.x
RUN curl -fsSL https://deb.nodesource.com/setup_20.x | bash - \
 && apt-get update && apt-get install -y nodejs \
 && npm -v && node -v

# Composer acostuma a vindre, però per si de cas:
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" \
 && php composer-setup.php --install-dir=/usr/local/bin --filename=composer \
 && rm composer-setup.php
