Installation
git clone https://github.com/shreeshau6/ImageGallery.git blog
cd blog
composer install
php artisan key:generate
Create a database and inform .env
php artisan migrate --seed to create and populate tables
php artisan serve to start the app on http://localhost:8000/