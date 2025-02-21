Invite de commande :

symfony new app --version="7.2.x" --webapp

docker-compose up -d --build

docker exec -it symfony_app bash

chown -R www-data:www-data /var/www/html
chmod -R 775 /var/www/html/var

