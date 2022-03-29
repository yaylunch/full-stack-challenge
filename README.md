
Yay Lunch Full Stack Code Challenge
========================================

## Welcome

Thanks for your interest in joining the Yay Lunch tech team! Part of our evaluation process is to set an open-ended challenge which will allow you to flex your creative muscles as well as demonstrate your coding skills.

If you get stuck or have questions as you are working on this challenge, please reach out to us. We are happy to help. Especially if you are struggling with setting up your local development environment.

Good luck and say Yay!

~The Yay Lunch Tech Team

## About this repo

This repo contains a simple todo list app featuring a [Vue.js](https://vuejs.org/) frontend and a [Laravel](https://laravel.com/) backend api.

## The challenge

Your challenge is to make an improvement to the todo application. Any improvement will do.

Here are some example ideas. Feel free to use one, or come up with your own!

- Enable tagging to categorize items
- Move completed items below incomplete items
- Add "details" to items
- Introduce subitems in a tree structure
- Improve the layout and design
- Provide the ability to add colors to items
- Make it possible to "star" priority items

We ask that you spend 3-4 hours on this challenge.

We're more interested in understanding your thinking and approach than the quality of your deliverable. To that end, it will be valuable for you to invest time in documenting your work, either in your copy of the repository or included in your email when you're finished.

We'll be available throughout your challenge period if you have any questions, want to discuss your approach, or are interested in pairing on a video call with screen-sharing.

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
