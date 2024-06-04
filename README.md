# NG - Plateforme Universitaire
## Introduction
NG est une plateforme web interactive et centralisée visant à moderniser le système éducatif au Maroc. Elle permet aux étudiants, professeurs et administrateurs des universités marocaines de gérer leurs activités quotidiennes, d'accéder à des informations importantes et de se connecter avec la communauté universitaire. La plateforme facilite également la collaboration entre les clubs de différentes universités.
## Fonctionnalités principales
- Gestion des cours et des notes: Accédez aux informations des cours, aux devoirs, aux notes et aux supports de cours.
- Communication et collaboration: Envoyez des messages aux professeurs, aux étudiants et à l'administration. Participez à des forums de discussion et à des événements virtuels.
- Gestion des clubs: Créez, rejoignez et gérez des clubs étudiants.
- Accès aux ressources universitaires: Consultez les actualités, les événements, les annonces et les ressources pédagogiques de l'université.
- Gestion des utilisateurs et des permissions: Les administrateurs peuvent créer, gérer et supprimer des comptes utilisateurs, gérer les clubs, les publications et les permissions.
## Technologies Utilisées

### Front-End

- **HTML** : Outils de développement web de base.
- **Tailwind CSS** : Framework CSS pour une application web réactive et cohérente.
- - **React** :  Librairie JavaScript pour construire des interfaces utilisateur dynamiques et réactives. 


### Back-End

- **Spring Boot** : Pour construire et maintenir rapidement l'application web.
- **Spring Data JPA** : Simplifie les interactions avec la base de données.
- **Spring Security** : Offre des fonctionnalités de gestion des utilisateurs et intègre de nombreux mécanismes de connexion.
- **Spring Mail** : Simplifie la configuration des serveurs de messagerie.
- **Kafka** : Gère le flux massif de données et les mises à jour en temps réel.
- **Hazelcast** : Améliore les performances de l'application en stockant les données fréquemment consultées en mémoire.

### Contrôle de Version

- **Git** : Système de gestion de versions distribué.

### Déploiement

- **Docker** : Conteneurisation et déploiement des services.

### Tests

- **JIRA** : Gestion de projet et suivi des bugs.

## Installation et configuration

### Prérequis
Avant de commencer, assurez-vous d'avoir installé les logiciels suivants :

- Node.js v14+
- npm v6+
- Java JDK 11+
- Docker
- Git
## Utilisation du projet
### Démarrage rapide
Pour lancer le projet localement, exécutez les commandes suivantes :
1. Clonez le dépôt Git du projet.
2. Installez les dépendances requises à l'aide de npm install.
3. Démarrez le serveur de back-end en exécutant npm start.
4. Démarrez le serveur de front-end en exécutant ng serve.
5. Accédez à l'application NG dans votre navigateur web à l'adresse http://localhost:4200.
