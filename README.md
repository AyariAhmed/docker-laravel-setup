## Run commands
- To Create Laravel app : 
 docker-compose run --rm composer create-project laravel/laravel .

* If There is a permission error related to storage/ change the following persmissions: 
    - chmod -R gu+w storage
    - chmod -R guo+w storage
    - php artisan cache:clear

* Start the App:
 docker-compose up -d --build server (the --build option is used to make sure of any untacked changes in dockerfiles)    