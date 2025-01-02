docker compose up --build -d

docker exec -it cms_backend bash 

composer install --no-dev --optimize-autoloader
php artisan migrate --force
chmod -R 777 storage bootstrap/cache

メモ
laravel11はapi.phpがないため手動で作成する必要がある
php artisan install:api