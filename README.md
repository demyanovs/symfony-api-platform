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

````
/api/docs.json?spec_version=3
````

````
curl -X GET 'https://localhost:8000/api' -H "accept: application/ld+json" | jq
````

````
php bin/console debug:config api_platform
````

make:user  
````
php bin/console make:user
````