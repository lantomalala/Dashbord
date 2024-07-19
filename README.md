# React Dashboard

Ce projet est un tableau de bord basé sur React avec un design moderne et réactif. Il comprend plusieurs pages et composants, tels que Home, Profile, FAQ, Chat, Pricing, Inbox, Invoice et Wizard.

![Dashboard Screenshot](https://raw.githubusercontent.com/lantomalala/Dashbord/master/captureDashbord.png)

## Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du dossier](#structure-du-dossier)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Fonctionnalités

- **Home**: Deux variantes avec différents widgets et statistiques.
- **Profile**: Page de profil utilisateur avec flux d'activité et statistiques.
- **FAQ**: Page de questions fréquemment posées.
- **Chat**: Interface de chat en temps réel.
- **Pricing**: Plans et options de tarification.
- **Inbox**: Interface de boîte de réception d'emails.
- **Invoice**: Page de gestion des factures.
- **Wizard**: Guide ou formulaire étape par étape.

## Installation

Pour commencer avec ce projet, suivez ces étapes :

1. Clonez le dépôt :
    ```sh
    git clone git@github.com:lantomalala/Dashbord.git
    ```
2. Accédez au répertoire du projet :
    ```sh
    cd Dashbord
    ```
3. Installez les dépendances :
    ```sh
    npm install
    ```

## Utilisation

Pour démarrer le serveur de développement, exécutez :
```sh
    npm start
 ```   
## Structure du dossier

Le projet a la structure de dossiers suivante :
```sh
    dashboard/
        ├── public/
        │   ├── index.html
        │   └── ...
        ├── src/
        │   ├── components/
        │   │   ├── Chat/
        │   │   ├── FAQ/
        │   │   ├── Home/
        │   │   ├── Inbox/
        │   │   ├── Invoice/
        │   │   ├── Pricing/
        │   │   ├── Profile/
        │   │   ├── Wizard/
        │   │   └── ...
        │   ├── App.js
        │   ├── index.js
        │   └── ...
        ├── .gitignore
        ├── package.json
        ├── README.md
        └── ...
 ```
## Contribuer

1. Forkez le dépôt.

2. Créez une nouvelle branche :
```sh
    git checkout -b feature/nom-de-votre-fonctionnalité
 ```
3. Apportez vos modifications.
4. Commitez vos modifications :
```sh
    git commit -m 'Ajout d'une fonctionnalité'
 ```
5. Poussez vers la branche :
```sh
    git push origin feature/nom-de-votre-fonctionnalité
 ```