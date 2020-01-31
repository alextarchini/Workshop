# Installation
## Installation de Laravel via composer
```bash
composer global require laravel/
installer
```

## Création d'un site avec Laravel CLI ou composer
```bash
laravel new LoveSon
```
ou 
```bash
composer create-project --prefer-dist laravel/laravel LoveSon
```

## Installation des resources front-end pour le système de login
module laravel/ui via composer
```bash
composer require laravel/ui --dev
```
création des views via php artisan
```bash
php artisan ui vue --auth
```

## Gestion des resources front-end
```bash
npm install
```
ou 
```bash
npm i
```
ensuite 
```bash
npm run dev
```
Cette commande va compiler les fichers scss et js en un seul fichier css et un seul fichier js. Laravel utilise webpack mais il propose un outil laravel-mix pour faciliter le développement. Si nécessaire, nous pouvons modifier le comportement webpack via le fichier webpack.mix.js

[Section suivante - configuration environnement](configuration_environnement.md)


