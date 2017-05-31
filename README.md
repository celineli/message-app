# Message app

## Description

Projet d'application qui permet d'afficher et de créer des messages.

## Installation des dépendances

    composer install

## Structure de données

message :

- id
- author
- date
- content

## Création de la base de données

    php app/console doctrine:database:create
    php app/console doctrine:schema:create


## Utilisation

Démarrez un serveur web de développement dans le dossier `web`

    php bin/console server:start
