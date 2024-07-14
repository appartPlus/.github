# Appart+

Bienvenue dans le dépôt GitHub de Appart+, une application similaire à Lodgify. Ce projet est structuré avec un frontend en Next.js et un backend en Laravel. Suivez les instructions ci-dessous pour contribuer efficacement au développement de l'application.

## Table des Matières

- [Aperçu](#aperçu)
- [Technologies Utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Contribution](#contribution)
- [Git Flow](#git-flow)
- [Règles de Commit](#règles-de-commit)
- [Support](#support)
- [Licence](#licence)

## Aperçu

Appart+ est une application de gestion immobilière, offrant des fonctionnalités avancées pour les propriétaires et les locataires. L'objectif est de faciliter la gestion des biens immobiliers grâce à une interface utilisateur intuitive et un backend robuste.

## Technologies Utilisées

- **Frontend**: Next.js
- **Backend**: Laravel
- **Base de données**: MySQL
- **Contrôle de version**: Git, Git Flow

## Installation

### Prérequis

- Node.js
- npm ou yarn
- PHP
- Composer
- MySQL

### Instructions

1. Clonez le dépôt du frontend:
    ```sh
    git clone https://github.com/organisation/appartPlus-frontend.git
    ```

2. Clonez le dépôt du backend:
    ```sh
    git clone https://github.com/organisation/appartPlus-backend.git
    ```

3. Installez les dépendances pour le frontend:
    ```sh
    cd appartPlus-frontend
    npm install
    ```

4. Installez les dépendances pour le backend:
    ```sh
    cd ../appartPlus-backend
    composer install
    ```

5. Configurez les variables d'environnement.

    - Pour le frontend, créez un fichier `.env.local` en vous basant sur `.env.example`.
    - Pour le backend, copiez `.env.example` en `.env` et modifiez-le selon vos configurations MySQL.

6. Démarrez les serveurs:

    - Frontend:
        ```sh
        cd ../appartPlus-frontend
        npm run dev
        ```

    - Backend:
        ```sh
        cd ../appartPlus-backend
        php artisan serve
        ```

## Contribution

Pour contribuer à ce projet, veuillez suivre les étapes suivantes :

1. Forkez le dépôt.
2. Clonez le dépôt du frontend ou du backend selon votre domaine de travail.
3. Créez une branche pour votre fonctionnalité (`git checkout -b feature/ma-fonctionnalité`).
4. Commitez vos modifications (`git commit -m 'Ajout de ma fonctionnalité'`).
5. Poussez sur la branche (`git push origin feature/ma-fonctionnalité`).
6. Ouvrez une Pull Request.

### Exigences de Contribution

- Assurez-vous que votre code suit les normes de codage définies.
- Ajoutez des tests pour toute nouvelle fonctionnalité si possible.
- Mettez à jour la documentation si nécessaire.

## Git Flow

Nous utilisons Git Flow pour organiser notre développement. Assurez-vous que Git Flow est installé sur votre machine. Suivez les instructions sur [ce site](https://danielkummer.github.io/git-flow-cheatsheet/index.fr_FR.html) pour plus de détails.

1. Initialisez Git Flow dans votre dépôt:
    ```sh
    git flow init
    ```

2. **Créer une nouvelle fonctionnalité** :
    ```sh
    git flow feature start ma-fonctionnalité
    ```

3. **Terminer une fonctionnalité** :
    ```sh
    git flow feature finish ma-fonctionnalité
    ```

Avant de pousser sur la branche `main`, ouvrez d'abord une Pull Request pour révision.

## Règles de Commit

- Utilisez des messages de commit clairs et concis.
- Format recommandé : `[Type] Courte description`.
  - **Types** : feat (nouvelle fonctionnalité), fix (correction de bug), docs (documentation), style (formatage, CSS, etc.), refactor (refactorisation de code), test (ajout de tests), chore (tâches de maintenance).

## Support

Si vous avez des questions ou avez besoin d'aide, veuillez ouvrir une [issue](https://github.com/organisation/appartPlus/issues) ou contacter l'équipe de développement.

