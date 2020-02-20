# Laravel + VueJs API CRUD 
<p>Simple API for Blog Post (CRUD) with Laravel 6.0, uses the API resources as backend and vue.js as front end. </p>

Quick Start
## Database Name 
laravel_api_blog

## Install Dependencies
- `composer install`
- `composer create-project giant41/laravel-api-blog`
- `cd laravel-api-blog`

## Run Migrations
`php artisan migrate`

## Import Articles
`php artisan db:seed`

## Add virtual host if using Apache

## If you get an error about an encryption key
`php artisan key:generate`

## Endpoints
List all articles with links and meta

- GET `api/articles`
- Get `single article`
- GET `api/article/{id}`
- Delete `article`
- DELETE `api/article/{id}`
- Add `article`
- POST `api/article`
- `title/body`
- Update `article`
- PUT `api/article`
- `article_id/title/body`
