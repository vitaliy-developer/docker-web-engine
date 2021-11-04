#
$ git clone https://github.com/laravel/laravel.git
$ mv laravel/ blog

#
$ docker-compose up --build 

#
http://localhost:6080/
Ceate db -> blog
Add name db -> blog/.env

#
RUN docker-compose exec web bash
$ php artisan key:generate
$ php artisan migrate

# 
http://localhost:8080/public/
http://localhost:8080/public/admin 
