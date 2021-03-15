# vue-laravel
vue laravel nextmedia app challenge
Vue 2.6 + Laravel 6 + Axios CRUD challenge app

See https://apple-watch.online Inspiration from https://github.com/herusdianto/laravel-vue-crud



Installation
Clone repo

Change to directory

cd vue-laravel-crud
Install dependencies
composer install
Copy .env file
cp .env.example .env
Modify DB_* value in .env with your database config.

Generate application key:

php artisan key:generate
Migrate
php artisan migrate
Install Node modules
npm install
Build
npm run prod
