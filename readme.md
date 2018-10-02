# Laravel Quickstart - Basic

## Quick Installation

    1. git clone https://github.com/DaveMitali/taskList OR download the repository from the link and unzip it.
    
    2. Open phpmyadmin and create a database _tasklist_.
    
    3. The folder contains a _.env.example_ file. Use Sublime Text or some editor to rename it to _.env_. Edit the following parameters in the file: DB_DATABASE=tasklist, DB_USERNAME as your MySQL username(default is root), DB_PASSWORD as the MySQL password.
    
    4. Goto the folder in command line.
    
    5. php artisan key:generate
    
    6. composer install
    
    7. php artisan migrate
    
    8. php artisan serve

    9. Go to http://localhost:8000/ to see the task list project.
