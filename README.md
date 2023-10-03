# J1_FullstackProject

## Introduction
- **Objectif :** Développer une application basée sur une architecture microservices pour offrir un service de gestion de tâches en ligne.
- **Objectifs spécifiques :**
  - Concevoir une API RESTful pour la gestion des tâches.
  - Utiliser des Design Patterns pour garantir la maintenabilité et l'évolutivité du code.
  - Mettre en place une architecture microservices pour la scalabilité et la flexibilité.
  - Gérer le code source avec Git et GitHub.

## Explication des Concepts

### API (Application Programming Interface)
- **Description :** Une API est un ensemble de règles et de protocoles qui permettent à différentes applications de communiquer entre elles. Dans ce projet, l'API sera utilisée pour permettre aux clients d'accéder aux fonctionnalités de gestion des tâches.

- **Schema :** 
Client         API         Système de Gestion de Tâches
  |            |                |
  |    Requête |-------------->|
  |            |                |
  |            |<--------------|
  |  Réponse  |                |

- **Utilisation :** L'API devra fournir des points d'entrée pour créer, lire, mettre à jour et supprimer des tâches, ainsi que pour récupérer la liste des tâches.

### Design Pattern
- **Description :** Les Design Patterns sont des solutions éprouvées pour des problèmes de conception courants en programmation. Ils permettent de structurer le code de manière à améliorer la maintenabilité et à faciliter l'ajout de nouvelles fonctionnalités.


- **Utilisation :** Dans ce projet, nous utiliserons des Design Patterns tels que le Modèle Vue-Contrôleur (MVC) pour organiser la logique de l'API et le Patron de Conception Singleton pour gérer les connexions à la base de données.

### Architecture Microservices
- **Description :** L'architecture microservices consiste à découper une application en petits services autonomes, chacun ayant sa propre responsabilité. Cela permet une évolutivité facile et une meilleure isolation des erreurs.

- **Schema :** 
        +-------------------+
        |  Microservice 1  |
        +-------------------+
               |    |
        +-------------------+
        |  Microservice 2  |
        +-------------------+

- **Utilisation :** Nous concevrons l'application de manière à ce que chaque fonctionnalité (par exemple, la gestion des tâches, l'authentification des utilisateurs, etc.) soit un microservice distinct.

### Git et GitHub
- **Description :** Git est un système de gestion de versions qui permet de suivre les modifications du code source au fil du temps. GitHub est une plateforme d'hébergement de code source basée sur Git qui facilite la collaboration entre développeurs.
- **Utilisation :** Nous utiliserons Git pour suivre l'historique des modifications du code et GitHub pour héberger le référentiel du projet, gérer les problèmes et les demandes de fusion, et faciliter la collaboration entre les membres de l'équipe.

