# Introduction
This project is a Ecommerce website built with Laravel 6, and VueJS.

# Installation
- Clone the repo and cd into it
- composer install
- Rename or copy .env.example file to .env
- php artisan key:generate
- Set your database credentials in your .env file
- Set your Braintree credentials in your .env file if you want to use PayPal. Specifically BT_MERCHANT_ID, BT_PUBLIC_KEY, BT_PRIVATE_KEY. If you don't, it should still work but won't show the paypal payment at checkout.
- Set your APP_URL in your .env file. This is needed for Voyager to correctly resolve asset URLs.
- Set ADMIN_PASSWORD in your .env file if you want to specify an admin password. If not, the default password is 'password'
- php artisan ecommerce:install. This will migrate the database and run any seeders necessary.
- npm install
- npm run dev
- npm run watch
- php artisan make:migration
- php artisan migrate
- php artisan db:seed
- php artisan storage:link
- php artisan server
- localhost:8000
- localhost:8000/admin/login
- Admin User/Password: admin@admin.com/password.
- Admin Web User/Password: adminweb@adminweb.com/password
