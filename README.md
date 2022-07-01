# Mise en place des mesure de sécuité Symfony



```
composer install
```

```
docker-compose up -d
```

ou bien configurer une bdd en personnalisant le .env ou .env.local

```

symfony console doctrine:database:create
symfony console doctrine:migrations:migrate
symfony console doctrine:fixtures:load
```


```
symfony serve
```


