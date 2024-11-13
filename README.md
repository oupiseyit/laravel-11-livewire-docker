
## Run this project 

docker-compose down && docker-compose up -d

## Run  bash
docker exec -it laravel_11_livewire_app bash

## Install Livewire

composer require livewire/livewire

php artisan livewire:publish --config

php artisan livewire:publish --assets

docker exec -it laravel-11-livewire-docker-app bash





