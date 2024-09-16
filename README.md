Laravel 11 Multi Auth Guard Using Breeze 
-------------------------------------------------------

<li> Step 1 - Laravel 11 installation</li>
<li>Step 2 - laravel breeze package</li>
<li>Step 3 - Model and migration for super admin and admin</li>
<li>Step 4 - Setup the schema inside the migrations and fillable property in the models</li>
<li>Step 5 - Create guards and providers in the auth.php</li>
<li>Step 6 - Implement authentication for the super admin</li>
<li>Step 7 - Implement authentication for the admin</li>
<li>Step 8 - Create middlewares and will have to register it</li>

# **For Run**

<li>1. Go to the project directory -> cd project-name</li>
<li>2. Copy .env.example file to .env and edit database credentials there</li>
<li>3. composer install</li>
<li>4. php artisan key:generate</li>
<li>5. php artisan migrate:fresh --seed</li>
<li>6. php artisan storage:link</li>
<li>7. npm install </li>
<li>8. php artisan serve & npm run dev </li>
