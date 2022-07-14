QuickApp - Simple Laravel User Management App Using Laravel Breeze and Spatie's        Laravel-Permissions

* Install Composer Dependencies: composer install

* Install NPM Dependecies: npm install

* Produce an .env file by simply copying the .env.xample into application root folder and name it as .env

* Execute command php artisan key:generate to generate APP Key to avoid API execution error

* On .env change APP_NAME and APP_URL to avoid routing issues ex: APP_NAME = "BE-EXAM-API" APP_URL = http://localhost/QuickApp - no need to execute php artisan serve command

* Run Database Migrations: php artisan migrate

To generate dummy data run seeder command:

* Run Seed/Factory Seeder For Admin Permissions seeds: php artisan db:seed --class=BasicAdminPermissionSeeder

