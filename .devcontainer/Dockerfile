FROM laravelsail/php84-composer:latest

# Crear usuari 'vscode' per compatibilitat amb Codespaces
RUN useradd -ms /bin/bash vscode \
    && echo "vscode ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER vscode
WORKDIR /var/www/html
