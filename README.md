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
<img width="1913" height="948" alt="Capture d&#39;écran 2024-12-10 163725" src="https://github.com/user-attachments/assets/82cb16fa-5eaf-440f-b6db-856c05d709aa" />
<img width="1919" height="831" alt="Capture d&#39;écran 2024-12-10 163758" src="https://github.com/user-attachments/assets/c8114ec2-ce20-4c23-80e2-a337ef8cd5f7" />
<img width="1916" height="887" alt="Capture d&#39;écran 2024-12-10 163839" src="https://github.com/user-attachments/assets/78d3fc03-1683-485d-a9c1-0f9d48168384" />
<img width="1156" height="906" alt="Capture d&#39;écran 2024-12-10 163915" src="https://github.com/user-attachments/assets/79e002c2-f7ce-435d-8bb5-e1f93d11ba2e" />
