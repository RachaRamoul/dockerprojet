FROM alpine:latest

# Installation des dépendances nécessaires et de PHP
RUN apk add --no-cache php php-session php-pdo php-pdo_mysql php-pdo_pgsql php-pdo_sqlite php-mysqli php-json php-mbstring

# Téléchargement et installation d'Adminer
WORKDIR /var/www/html
RUN wget https://github.com/vrana/adminer

# Exposer le port d'Adminer
EXPOSE 8080

#lancer Adminer
CMD ["php", "-S", "0.0.0.0:8080"]
