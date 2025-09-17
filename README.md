Portfolio Spring Boot + React
Description

Ce projet est un portfolio personnel développé avec une architecture frontend-backend :

Frontend : React

Backend : Spring Boot

L'idée est de présenter mes projets, compétences, parcours, avec une interface web moderne.

Fonctionnalités

Affichage des pages “Accueil”, “À propos”, “Compétences”, “Projets”, “Contact”.

Backend fournit des données via API REST (informations personnelles, liste de projets, compétences, etc.).

Formulaire de contact pour envoyer des messages.

Responsive design.

Technologies utilisées

Frontend : React, JavaScript, CSS (ou un framework UI selon ce que tu utilises)

Backend : Java, Spring Boot, Spring Web, Spring Data (selon si tu utilises une base de données)

Base de données : (par exemple MySQL / PostgreSQL / H2)

Déploiement (selon ce que tu choisis) : Heroku / AWS / Digital Ocean ou autre

Structure du projet
portfolio_springboot-rectt/
├── client/         # code React
│   ├── src/
│   ├── public/
│   └── package.json
├── server/         # code Spring Boot
│   ├── src/
│   ├── main/
│   ├── resources/
│   └── pom.xml (ou build.gradle)
└── README.md

Installation

Cloner le dépôt :

git clone https://github.com/bakirkammoun/portfolio_springboot-rectt.git


Backend :

Se placer dans server/

Configurer la base de données (ou fichier de configuration)

Lancer avec Maven / Gradle :

mvn spring-boot:run


ou

./mvnw spring-boot:run


Frontend :

Se placer dans client/

Installer les dépendances :

npm install


Lancer le serveur de développement :

npm start

Configuration

Fichier de configuration du backend pour définir la connexion à la base de données (URL, nom d’utilisateur, mot de passe).

Eventuellement, variables d’environnement pour l’URL de l’API dans le frontend.
