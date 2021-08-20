# blog

laravel + vue project

1. Run docker
   -> docker-compose up -d
2. Go to blog_backend_1 container
   -> docker exec -it blog_backend_1 /bin/sh
3. Access permision
   -> chmod -R 777 storage bootstrap/cache
4. generate artisan key
   -> php artisan key:generate
