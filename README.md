# laravel_auth
Laravel Authentication Simple

create database name authwebtest<br>
cp .env.example .env<br>

open .env and change :<br>
DB_DATABASE=authwebtest<br>
DB_USERNAME=[username database local]<br>
DB_PASSWORD=[password database local]<br>

chmod -R 777 bootstrap/cache/ storage/<br>
php artisan key:generate<br>
php artisan migrate<br>
