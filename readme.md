Installation =>

    type git clone https://github.com/sunil16/laravel5.4_demo_application.git projectname to clone the repository
    type cd projectname
    type composer install
    type composer update
    copy .env.example to .env

    if you use MySQL in .env and database.php file :

    config/database.php =>
    'database' => env('DB_DATABASE', 'your_database_name'),
    'username' => env('DB_USERNAME', 'user_name'),
    'password' => env('DB_PASSWORD', 'sql_password'),

    .env =>
    DB_DATABASE=your_database_name
    DB_USERNAME=user_name
    DB_PASSWORD=sql_passwsord

    after successful configuration =>

    http://localhost:8000/book

   ![myimage-alt-tag](https://github.com/sunil16/laravel5.4_demo_application/blob/master/public/img/create.png)

   
   Click edit button =>

  ![myimage-alt-tag](https://github.com/sunil16/laravel5.4_demo_application/blob/master/public/img/edit.png)
