# Argent Bank — Projet 11 — OpenClassRooms

Développement de l’interface utilisateur pour Argent Bank, une banque en ligne fictive. Ce projet utilise React et Redux pour la gestion de l’authentification et du profil utilisateur.

## Table des matières

- [Présentation](#présentation)
- [Technologies](#technologies)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Données pré-remplies](#données-pré-remplies)
- [Documentation de l’API](#documentation-de-lapi)
- [Ressources de conception](#ressources-de-conception)
- [Objectifs du projet](#objectifs-du-projet)
- [Green Code](#green-code)
- [Auteur](#auteur)

## Présentation

Ce projet fait partie du parcours Développeur Intégrateur Web chez OpenClassRooms. L'objectif est de développer le front-end d'une application bancaire en utilisant React et Redux pour créer une expérience utilisateur dynamique et réactive. Le projet consiste à intégrer le front-end avec le back-end via des appels API.

## Technologies

Argent Bank utilise les technologies suivantes :

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Node.js v12](https://nodejs.org/en/)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community)
- [Swagger](https://swagger.io/)

## Prérequis

Avant de commencer, assurez-vous d’avoir installé les versions correctes de Node.js et MongoDB. Vous pouvez vérifier les versions installées en utilisant les commandes suivantes :

```bash
# Vérifiez la version de Node.js
node --version

# Vérifiez la version de MongoDB
mongo --version
```

## Installation

1. Forkez ce dépôt.
2. Clonez le dépôt sur votre ordinateur.
3. Ouvrez une fenêtre de terminal dans le projet cloné.
4. Exécutez les commandes suivantes pour installer les dépendances et démarrer le serveur de développement local :

```bash
# Installez les dépendances
npm install

# Démarrez le serveur de développement local
npm run dev:server

# Remplissez la base de données avec deux utilisateurs
npm run populate-db
```

Votre serveur devrait maintenant fonctionner à l’adresse [http://localhost:3001](http://localhost:3001) et vous devriez avoir deux utilisateurs dans votre base de données MongoDB.

## Données pré-remplies

Une fois que vous avez exécuté le script `populate-db`, vous devriez avoir deux utilisateurs dans votre base de données :

### Tony Stark

- Prénom : `Tony`
- Nom : `Stark`
- Email : `tony@stark.com`
- Mot de passe : `password123`

### Steve Rogers

- Prénom : `Steve`
- Nom : `Rogers`
- Email : `steve@rogers.com`
- Mot de passe : `password456`

## Documentation de l’API

Pour en savoir plus sur le fonctionnement de l’API, une fois que vous avez démarré votre environnement local, vous pouvez visiter : [http://localhost:3001/api-docs](http://localhost:3001/api-docs).

## Ressources de conception

Le HTML et le CSS statiques pour la plupart du site se trouvent dans le dossier `/designs`.

Pour certaines fonctionnalités dynamiques, comme la modification du nom d’utilisateur, un mock-up est disponible dans `/designs/wireframes/edit-user-name.png`.

Pour le modèle d’API que vous proposerez pour les transactions, la maquette se trouve dans `/designs/wireframes/transactions.png`.

## Objectifs du projet

1. **Configuration des routes API** pour la communication client-serveur.
2. **Gestion des données avec Redux** pour assurer le bon fonctionnement du front-end.
3. **Affichage des données du back-end** sur l’interface via des appels API.
4. **Mise en place du tableau de bord des utilisateurs** avec une application web réactive et responsive.

## Green Code

Dans ce projet, nous mettons en œuvre des bonnes pratiques de Green Code. Voici deux aspects clés à considérer :

1. **Optimisation des images** : Veillez à ce que les images soient optimisées en termes de poids et de dimensions pour réduire la consommation de ressources.
2. **Composants réutilisables** : Créez des composants réutilisables autant que possible pour optimiser le code et réduire la duplication.

## Auteur

Ce projet a été réalisé par [Mikaël Posty](https://portfolio.mikepixel.dev/). N'hésitez pas à visiter mon [portfolio](https://portfolio.mikepixel.dev/) pour découvrir d'autres projets et en savoir plus sur mon travail.
