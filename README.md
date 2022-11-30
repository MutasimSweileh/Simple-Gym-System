# Simple Gym System

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

A Simple Gym System as the Laravel project for Open Source Application Development Track, ITI intake 42. Follow this link to see deployment on Heroku

<br>

## Project Deployment

```
http://still-coast-73893.herokuapp.com/login
```

```
Admin Email: abdo@gmail.com
Admin Password: abdo1234
```

# Contents

-   [ERD]()
-   [Running the Project]()
-   [Built with]()
-   [Authors ]()

## ERD & Mapping

![gym edited](https://user-images.githubusercontent.com/97949768/156903803-d0e015de-a274-4a9a-a25c-de8434383991.png)

# Running the project

## .env file

After making clone to our project go to .env file and make sure you edit these parameters to suit yours.

-   **DB_DATABASE=gym**
-   **DB_USERNAME=root**
-   **DB_PASSWORD=**

-   **DB_HOST=127.0.0.1**
-   **DB_PORT=3306**

Run this command in your terminal

```
composer install
```

</br>

### Admin LTE

</br>

```
npm install
```

If you faced problems in setuping npm make sure you've node js

```
npm run dev
```

```
npm install admin-lte@^3.2 --save
```

```
npm install --save @fortawesome/fontawesome-free
```

```
npm run dev
```

### Laravel Permissions

</br>

```
composer require spatie/laravel-permission
```

```
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
```

```
php artisan optimize:clear
```

```
php artisan migrate
```

### Laravel Ban

</br>

```
composer require cybercog/laravel-ban
```

```
php artisan vendor:publish --provider="Cog\Laravel\Ban\Providers\BanServiceProvider" --tag="migrations"
```

```
php artisan migrate
```

### DataTables

</br>

```
 composer require yajra/laravel-datatables-oracle:"~9.0"
```

```
php artisan vendor:publish --provider="Yajra\DataTables\DataTablesServiceProvider"
```

### Laravel Sanctum

</br>

```
composer require laravel/sanctum
```

```
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
```

```
php artisan migrate
```

### To add new admin

</br>

```
php artisan create:admin
```

### To run seeders

</br>

```
php artisan db:seed
```

### Add Stripe key

In .env file add

```
STRIPE_KEY=pk_test_51KZbWdGerl36jGBlSUe3rMyBApbtz9gPiGLrY3dSKyCRZKuqADbV9JG3gHNrtxxh94WD703gxBv3NZ7WzVTMqZUV00bCzwzL6F
```

```
STRIPE_SECRET=sk_test_51KZbWdGerl36jGBlurnj9wlsLRgZS70wmhiSNkP5zzwKlSxCvY3GwZr1YCutrdfulSVJE8hSyzGppuYIRQ1LJ70U00gKEGdZCa
```

Then run these commands

```
composer require laravel/cashier
```

```
composer require stripe/stripe-php
```

In the end, don't forget to run this important command

```
php artisan serve
```

</br>
</br>

## Built With

-   [Laravel]()
-   [Admin LTE]()
-   [Stripe]()
-   [Laravel Sanctum ]()
-   [Laravel Ban ]()
-   [Laravel Permissions ]()

</br>
</br>

## Authors

-   **Abdeladl Mounir Abdeladl Shaheen**
-   **Abdelrahman Magdy Ibrahim Eldesouky**
-   **Ahmed Abdelfatah Abdelfatah Ali Elshopaky**
-   **Ahmed Hamdy Abd elkader Ashour**
-   **Asmaa Ebrahim Abdelhamid Ebrahim**
-   **Ali Tarek Ahmed Hussein**
-   **Mutasim Mohamed**
