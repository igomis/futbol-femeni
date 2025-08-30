FROM laravelsail/php84-composer:latest

# Crear usuari sail amb UID 1337 (igual que a Sail en local)
RUN useradd -ms /bin/bash -u 1337 sail \
    && echo "sail ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER sail
WORKDIR /var/www/html

