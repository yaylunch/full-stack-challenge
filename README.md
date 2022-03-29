## About This repo:

This repo contains a simple todo list app featuring a [Vue.js](https://vuejs.org/) frontend and a [Laravel](https://laravel.com/) backend api.

## Project setup

### Prerequisites

Composer: [https://getcomposer.org/](https://getcomposer.org/)
MySQL: [https://www.mysql.com/](https://www.mysql.com/)

### Installation

clone the repo 
```
https://github.com/yaylunch/full-stack-challenge.git
```


Then cd into the folder with this command-

```
cd full-stack-challenge
```

Then do a composer install

```
composer install
```

copy .env.example file and rename it to .env
and make a new database in mySql database, and name it what it ever you want , make sure that this name match in your .env file .

make migration for the tables 

```
php artisan migrate
```

generate key 

```
php artisan key:generate
```


Then do a npm install

```
npm install
```
## Run server

Run server using this command-

```
php artisan serve
```
### for the front end part you need to open another terminal for the same project and make :
```
npm run hot
```

Then go to `http://localhost:8000` from your browser and see the app.
