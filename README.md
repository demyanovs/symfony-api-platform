# Symfony API Platform

### Setup

```
composer install
```

### Start web server

```
symfony serve -d
```

## Generating the Entity
````
composer require api
````

````
composer require maker --dev
````

````
php bin/console make:entity
````

````
php bin/console doctrine:database:create
````

````
php bin/console make:migration
````

````
php bin/console doctrine:migrations:migrate
````