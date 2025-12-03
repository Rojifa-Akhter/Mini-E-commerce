# Mini E-commerce API

## Setup Instructions
1. Clone repo
2. Run `composer install`
3. Copy `.env.example` to `.env` and setup DB
4. Run `php artisan key:generate`
5. Run `php artisan migrate`
6. Run `php artisan db:seed`
7. Run `php artisan serve`

## Tools/Versions
- PHP 8.2
- Laravel 12
- MySQL 8
- Postman

## API Endpoints
- POST /api/register - http://127.0.0.1:8000/api/register
- POST /api/login - http://127.0.0.1:8000/api/login
- GET /api/products - http://127.0.0.1:8000/api/products?search=Generic Fresh Soap
- POST /api/products (Admin) - http://127.0.0.1:8000/api/products
- POST /api/orders - http://127.0.0.1:8000/api/orders

## Authentication
Use Bearer Token from login/register responses.
