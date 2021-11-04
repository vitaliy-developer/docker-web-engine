# Clone the project
- $ git clone https://github.com/laravel/laravel.git
- $ mv laravel/ blog
- $ docker pull php

# We build on a project and launch
- $ docker-compose up --build 

# We create a database
[localhost:6080]
- Ceate db -> blog
- Add name db -> blog/.env

# We go to our service
- $ docker-compose exec web bash
- $ php artisan key:generate //FIX: chown -R www-data:www-data .
- $ php artisan migrate

# We go to our project 
- http://localhost:8080/public/
- http://localhost:8080/public/admin 
