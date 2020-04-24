Setup:

git clone https://github.com/EnDeLMaN/train.git

composer update --lock

 .env file:

cp .env.example .env

php artisan key:generate

php artisan migrate
