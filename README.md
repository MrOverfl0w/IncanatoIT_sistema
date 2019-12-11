# IncanatoIT_sistema

## Sales system - Web development course project

- Laravel 6.4.0
- PHP 7.2.24 updated (7.4.0)
- Vue.js 2.6.10
- MySQL 5.7.28 replaced (MariaDB 10.4.10)

### Installation

Run all commands inside the project's root folder

1. #### Download the project's dependencies

   ``` Bash
   npm install
   ```

2. #### Create /vendor directory

   ``` Bash
   composer install
   ```

3. #### Configure .env file

    Duplicate the `.env.example` file and rename it to `.env`.  
    Modify it acording to your server configuration.

4. #### Run migrations

    ``` Bash
    php artisan migrate
    ```

5. #### Build the project

    ``` Bash
    npm run dev
    ```
