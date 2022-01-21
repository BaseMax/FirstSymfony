# First Symfony PHP

### Start Using

Create a new project using `composer create-project symfony/skeleton`.

And install `composer require symfony/maker-bundle --dev` and `composer require orm` to easily add entity files.

If you want to create a new Model: `php bin/console make:entity`

If you want to migrate and update the database: `php bin/console make:migration` and `php bin/console doctrine:migrations:migrate`.

Next:

```bash
$ symfony server:ca:install
$ symfony server:start
```

And open `https://localhost:8000/` in browser.

### Read more

- https://symfony.com/doc/current/setup/symfony_server.html
- https://symfony.com/download
- https://www.youtube.com/watch?v=4m3qUkIyPY8

