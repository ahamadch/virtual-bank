## About Project

This project is about a virtual banking system using Laravel 5.8 with minimal options
This includes modules like:
 - [Registration]()
 - [Login]()
 - [Home]()
 - [Deposit]()
 - [Withdraw]()
 - [Statement]()
 - [Logout]()


## Installing Project

To get started, we need composer (https://getcomposer.org/) to install the packages.
After installing composer, open terminal and type: ``` composer install ```. This will install all the needed packages. After that we need to run ``` npm install ```.

## Directory Permissions

After installing the project, you may need to configure some permissions. Directories within the `storage` and the `bootstrap/cache` directories should be writable by your web server or Laravel will not run.

## Application Key
The key can be set in the `.env` environment file. If you have not renamed the `.env.example` file to `.env`, you should do that now.
The next thing you should do after installing the  is set your application key to a random string. If you installed Laravel via Composer or the Laravel installer, this key has already been set for you by the ```php artisan key:generate``` command.

## Running Migrations
To run all of your outstanding migrations, execute the migrate Artisan command:

```php artisan migrate```

## Run the Project

If you have PHP installed locally and you would like to use PHP's built-in development server to serve your application, you may use the serve Artisan command. This command will start a development server at http://localhost:8000:

Run ``` php artisan serve ``` to run the application.
