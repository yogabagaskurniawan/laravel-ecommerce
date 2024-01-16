# Laravel 8 | PHP 7.4 - Ecommerce application

## Screenshots

<!-- ![preview img](/preview.png) -->

![alt text](https://github.com/yogabagaskurniawan/Quick_count/blob/master/public/documentasi/screencapture-quick-count-test-2023-11-22-15_15_49.png?raw=true)

## feature

-   Our e-commerce platform features a user-friendly shopping cart for easy checkout.
-   Explore the convenience of real-time shipping cost calculations through the Raja Ongkir API, ensuring transparency in your delivery charges.
-   Complete your transactions securely with the seamless payment gateway provided by Midtrans.

## Run Locally

Clone the project

```bash
  git clone https://github.com/yogabagaskurniawan/laravel-ecommerce.git project-name
```

Go to the project directory

```bash
  cd project-name
```

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Login

-   email = admin@example.com
-   password = 123
