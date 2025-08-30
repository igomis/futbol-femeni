FROM laravelsail/php84-composer:latest

# Crear usuari sail (UID 1337 com a Sail per defecte)
RUN adduser -u 1337 -D -s /bin/sh sail \
    && echo "sail ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER sail
WORKDIR /var/www/html
