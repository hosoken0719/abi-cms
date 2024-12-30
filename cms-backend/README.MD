docker compose up --build -d

docker exec -it cms-backend bash 

php artisan migrate --force
chmod -R 777 storage bootstrap/cache