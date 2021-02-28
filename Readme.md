### Install
```git clone https://github.com/Dou-xx/docker-laravel.git```
<br>
```cd docker-laravel```
<br>
```mkdir database```
<br>
```mkdir laravel```
<br>
Install project to folder 'laravel'
### Build
``` sudo docker-compose up --build ```
### Run containers
``` sudo docker-compose up -d```
### App
```sudo docker-compose exec app bash```
<br>
``` php artisan migrate ``` ...
### MySQL
```sudo docker-compose exec db bash```
<br>
```mysql -u root -p``` ...
### Laravel settings .env
#### Database:
```
DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=123123
```