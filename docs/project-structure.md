# Structure de projet php-symfony 
```bash 
symfoblog/
├── assets
├── bin
├── compose.override.yaml
├── compose.yaml
├── composer.json
├── composer.lock
├── config
├── importmap.php
├── migrations
├── phpunit.dist.xml
├── public
├── src
│   ├── Controller
│   ├── Entity
│   ├── Kernel.php
│   └── Repository
├── symfony.lock
├── templates
├── tests
├── translations
└── var
```
## public/
Racine publique du site, où est exposé le index.php qui démarre l’application (point d’entrée web).

## assets/
Contient les fichiers front-end (css, html, js, images)  avant qu’ils ne soient compilés.

## bin/
 Contient des scripts exécutables comme console, utilisé pour les commandes Symfony CLI.

## config/
Contient tous les fichiers de configuration Symfony (services, routes, packages…).

## compose.override.yaml
Surcharge le fichier `compose.yaml` pour adapter la configuration Docker localement sans modifier le fichier principal.

## compose.yaml (docker compose)
 Décrit les services Docker (comme base de données, serveur web) nécessaires au projet.

 ## compose.json
Liste les dépendances PHP du projet et les métadonnées (nom, scripts, librairies…).

## phpunit.dist.xml
Fichier de configuration pour PHPUnit, utilisé pour lancer les tests automatisés.

## composer.lock
Fige les versions exactes des dépendances installées, pour une reproductibilité  et identique.

## 