# Laravel PHP Container

## Requirements

- Docker

## How to run

Run this container whit the following command: 

- `docker container run --rm -ti -p 8000:8000 -v $(pwd):./ --user local lorenzocalamandrei/laravel-php bash`

After that you can use composer to initialize it or use the pre-installed laravel cli with `laravel new project` for example.
Otherwise you can proceed as you prefer.

## Contributors

- Lorenzo Calamandrei <nexcal.dev@gmail.com>
