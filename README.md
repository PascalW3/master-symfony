# Master Symfony

Pour récupérer le projet en local :

```bash
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```

Ne pas oublier de créer un fichier ```.env.local``` avec les accès de la base de données.
