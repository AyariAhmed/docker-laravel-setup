## Run commands
- To Create Laravel app : 
 docker-compose run --rm composer create-project laravel/laravel .

* If There is a permission error related to storage/ change the following persmissions: 
    - chmod -R gu+w storage
    - chmod -R guo+w storage
    - php artisan cache:clear
    