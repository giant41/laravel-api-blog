Simple Blog Post API
Laravel 6.0 API that uses the API resources as backend and vue.js as front end. 
This is an API for an blog article CRUD app

Quick Start
# Database Name 
laravel_api_blog

# Install Dependencies
composer install

# Run Migrations
php artisan migrate

# Import Articles
php artisan db:seed

# Add virtual host if using Apache

# If you get an error about an encryption key
php artisan key:generate


# Endpoints
List all articles with links and meta

GET api/articles

Get single article

GET api/article/{id}

Delete article

DELETE api/article/{id}

Add article

POST api/article

title/body

Update article

PUT api/article
article_id/title/body
