# ENAA Skills - Application de gestion des compétences

## Description du projet

ENAA Skills est une application microservice développée pour gérer le suivi d’acquisition des compétences et sous-compétences des collaborateurs au sein de ENAA.  
Ce service permet de créer, organiser et suivre les compétences (C1 à C8) et leurs sous-compétences, visualiser leur progression, évaluer les acquis, et identifier les axes de formation à renforcer.

Ce microservice fait partie d’une plateforme plus large dédiée à l’évaluation des formations internes.

---

## Fonctionnalités principales

- Création, mise à jour, suppression des compétences et leurs sous-compétences associées.
- Consultation et modification du statut de validation de chaque sous-compétence.
- Calcul automatique du statut global d’une compétence en fonction des sous-compétences validées.
- Consultation d’un tableau de bord synthétique des validations par apprenant.
- Export de rapports de suivi de progression.
- Gestion des erreurs et validation des données.
- Documentation des API avec Swagger.

---

## Technologies utilisées

- **Backend** : Spring Boot, Spring Data JPA  
- **Base de données** : PostgreSQL / MySQL  
- **Tests unitaires** : JUnit, Mockito  
- **Conteneurisation** : Docker + docker-compose  
- **Documentation API** : Swagger  

---

## Prérequis

- Java 17 ou supérieur
- Maven ou Gradle
- Docker & Docker Compose
- PostgreSQL ou MySQL (conteneurisé via Docker ou installation locale)

---

## Installation et lancement

1. Cloner le dépôt :  
   ```bash
   git clone https://github.com/khalidboumaghdar/ENAA_SKills.git
   cd ENAA_SKills

