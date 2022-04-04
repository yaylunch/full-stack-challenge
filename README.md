
Yay Lunch Full Stack Code Challenge
========================================

Greetings and salutations!

Thanks for your interest in joining the Yay Lunch tech team! Part of our evaluation process is to set an open-ended challenge which will allow you to flex your creative muscles as well as give you an opportunity to demonstrate your coding skills. We think (and hope you agree) that this is better than asking you to scribble algorithms on a whiteboard in an interview setting.

We encourage you to spend no more than 4-5 hours on this challenge. We realize that this is still a significant investment of effort on your part, but one we hope will be worthwhile for both you and us. Even if you don't end up joing the team, you are more than welcome to use what you produce for this challenge in your personal portfolio.

Most importantly, if you get stuck or have questions as you are working on this challenge, please reach out to us. We are happy to help. Especially if you are struggling with setting up your local development environment.

Good luck and Say Yay!
<br>
The Yay Lunch Tech Team
<br>
<br>
## About this repo
This repo contains a simple todo list app featuring a [Vue.js](https://vuejs.org/) frontend and a [Laravel](https://laravel.com/) backend api.
<br>
<br>
## Project setup
### Prerequisites

- Composer: https://getcomposer.org/
- MySQL: https://dev.mysql.com/doc/refman/8.0/en/installing.html
- MySQL Shell: https://dev.mysql.com/doc/mysql-shell/8.0/en/mysql-shell-install.html 
    - Make sure you can run the `mysql` command in your terminal (if not, add it to your operating system's PATH)

### Installation

1. Clone the repo 
    ```
    git clone https://github.com/yaylunch/full-stack-challenge.git
    ```


2. Then `cd` into the folder with this command-
    ```
    cd full-stack-challenge
    ```

3. Install Composer dependencies
    ```
    composer install
    ```

4. Use MySQL Shell to create a new MySQL database, and name it what it ever you want ([Need Help?](https://www.mysqltutorial.org/mysql-create-database/))

5. Copy `.env.example` file, rename it to `.env` and make sure that the `DB_DATABASE`, `DB_USERNAME`, and `DB_PASSWORD` variables in it matches the database and MySQL/database user you created.

6. Run the database migrations
    ```
    php artisan migrate
    ```

7. Generate the application key 
    ```
    php artisan key:generate
    ```

8. Install NPM dependencies
    ```
    npm install
    ```
<br>

## Running the development environment

Run the backend server
```
php artisan serve
```

In a new terminal, run the front end (be sure you are in the `full-stack-challenge` directory):
```
npm run hot
```

Then go to `http://localhost:8000` from your browser to see the app.
