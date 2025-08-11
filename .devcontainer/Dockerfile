FROM mcr.microsoft.com/devcontainers/php:8.2

# Instal·lem Node 18 i npm
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - \
 && apt-get install -y nodejs

# Instal·lem Composer (ja ve normalment, però per si de cas)
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" \
 && php composer-setup.php --install-dir=/usr/local/bin --filename=composer \
 && rm composer-setup.php
