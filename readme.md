# content-management-system

Content management system for laravel developers'. It's easy to install and run. 

### Server Requirements

The Laravel framework has a few system requirements. Of course, all of these requirements are satisfied by the Laravel Homestead virtual machine, so it's highly recommended that you use Homestead as your local Laravel development environment.

However, if you are not using Homestead, you will need to make sure your server meets the following requirements:

```
PHP >= 5.6.4
OpenSSL PHP Extension
PDO PHP Extension
Mbstring PHP Extension
Tokenizer PHP Extension
XML PHP Extension
```

### Installing

Run create-project command with composer to install this project.

Here is the full installation command -

```
composer create-project ratulhasan/laravel-cms
```

Open your terminal or cmd and run 

```
compposer install
```
```
php artisan key:generate
```

Now rename .env.example to .env and change this options bellow within your .env,

```
DB_DATABASE=homestead // your database name 
DB_USERNAME=homestead // your database user name 
DB_PASSWORD=secret // your database password 
```

```
MAIL_DRIVER=smtp // change it as your desire MAIL DRIVER
MAIL_HOST=smtp.mailtrap.io // change it as your desire MAIL HOST
MAIL_PORT=2525 // change it as your desire MAIL PORT
MAIL_USERNAME=null // change it as your desire MAIL USERNAME
MAIL_PASSWORD=null // change it as your desire MAIL PASSWORD
```

Now run 

```
php artisan migrate
```

```
php artisan db:seed
```

now run project.

### Happy coding

## Author

**<a href='https://besofty.com' target='_blank'>Ratul Hasan</a>** | **<a href='mailto:ratuljh@gmail.com'>Email</a>**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details