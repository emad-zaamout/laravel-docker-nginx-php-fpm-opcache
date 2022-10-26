
## Laravel Docker Nginx PHP-FPM OP_CACHE

Laravel Docker Nginx build using PHP-FPM and OP_CACHE. This build delivers top performance.


## How to use?

Step 1: Create a new Laravel project

Step 2: Pull this repo `git pull https://github.com/emad-zaamout/laravel-docker-nginx-php-fpm-opcache`

Step 3: Adjust your env variables. Make sure you set your database env vars. Add any values as the database will be created per your env var values.
```
# Example Values
DB_CONNECTION=mysql
DB_HOST=database <----------- This is important. Set this value.
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=homestead
DB_PASSWORD=secret

```

Run
`docker compose build  && docker compose up --force-recreate -d`

Default PHP port is 8000. Connect via `http://127.0.0.1:8000` or `http://localhost:8000`
Default DB port is 3306.



