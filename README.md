Laravel 11 Multi Auth Guard Using Breeze 
-------------------------------------------------------

Step 1 - Laravel 11 installation
Step 2 - laravel breeze package
Step 3 - Model and migration for super admin and admin
Step 4 - Setup the schema inside the migrations and fillable property in the models
Step 5 - Create guards and providers in the auth.php
Step 6 - Implement authentication for the super admin
Step 7 - Implement authentication for the admin
Step 8 - Create middlewares and will have to register it

# **For Run**

1. Go to the project directory -> cd project-name
2. Copy .env.example file to .env and edit database credentials there
3. composer install
4. php artisan key:generate
5. php artisan migrate:fresh --seed
6. php artisan storage:link
7. php artisan serve 
