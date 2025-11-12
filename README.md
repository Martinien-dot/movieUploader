#  movieUploader

**movieUploader** est une application simple permettant de :

téléverser des films (vidéos et affiches) depuis une interface React + TypeScript ;

sauvegarder les informations dans une base de données PostgreSQL via une API Spring Boot REST ;

afficher et lire les films directement depuis l’interface web.

## Technologies utilisées
### Backend :

Spring Boot 3 (REST API)

PostgreSQL (base de données)

Swagger (documentation API)

Docker Compose (pour la base de données)

### Frontend :

React + TypeScript

Vite

Tailwind CSS

Axios (requêtes HTTP vers l’API)

Fonctionnalités

Téléversement de vidéos et affiches

Sauvegarde des données dans PostgreSQL

Lecture des vidéos dans React

API RESTful documentée avec Swagger

## Installation et exécution
### 1. Lancer la base de données
docker-compose up -d

### 2. Lancer le backend
cd moviesupload
mvn spring-boot:run


L’API est disponible à l’adresse :

http://localhost:8080/api/movies

### 3. Lancer le frontend
cd frontend
npm install
npm run dev


L’application est accessible à l’adresse :

http://localhost:5173

## Documentation API

Swagger est disponible à l’adresse suivante :

http://localhost:8080/swagger-ui.html

## Auteur

**Kossi Martinien GABA**
Projet d’apprentissage : Spring Boot, React, PostgreSQL et Docker.
