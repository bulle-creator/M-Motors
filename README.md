# M-Motors Application

## Description

M-Motors est une application web développée en Java permettant la gestion de :

* la vente de véhicules d’occasion,
* la location longue durée avec option d’achat,
* la gestion des dossiers clients,
* le suivi des demandes,
* ainsi que l’administration des véhicules et utilisateurs.

L’objectif du projet est de proposer une plateforme moderne, sécurisée et entièrement dématérialisée.

---

# Fonctionnalités

## Espace Client

### Gestion des véhicules

* Consultation des véhicules disponibles
* Recherche multicritère :

  * marque
  * modèle
  * prix
  * kilométrage
  * type (vente/location)

---

## Achat de véhicule

Le client peut :

* créer un compte,
* déposer un dossier d’achat,
* télécharger les documents nécessaires,
* suivre l’avancement du dossier.

---

## Location de véhicule

Le client peut :

* choisir une voiture en location,
* sélectionner les options disponibles,
* déposer son dossier,
* suivre sa demande.

### Services inclus

* Assurance tous risques
* Assistance dépannage
* Entretien et SAV
* Contrôle technique

---

## Back-Office Administrateur

L’administrateur peut :

* ajouter des véhicules,
* modifier des véhicules,
* supprimer des véhicules,
* basculer un véhicule :

  * vente → location
  * location → vente
* valider/refuser les dossiers clients,
* gérer les utilisateurs.

---

# Architecture du projet

## Architecture MVC

Le projet suit une architecture MVC :

* Model → gestion des données
* View → interface utilisateur
* Controller → logique métier

---

# Technologies utilisées

## Backend

* Java 17
* Spring Boot
* Spring MVC
* Spring Security
* Hibernate / JPA

---

## Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

---

## Base de données

* MySQL

---

## Outils

* Maven
* Git
* GitHub
* Postman

---

# Structure du projet

```bash
M-Motors/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.mmotors/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── repository/
│   │   │       ├── model/
│   │   │       └── security/
│   │   │
│   │   └── resources/
│   │       ├── templates/
│   │       ├── static/
│   │       └── application.properties
│
├── pom.xml
└── README.md
```

---

# Installation du projet

## Prérequis

Installer :

* Java JDK 17
* Maven
* MySQL
* Git

---

# Cloner le projet

```bash
git clone https://github.com/bulle-creator/m-motors.git
```

---

# Configuration de la base de données

Créer une base de données MySQL :

```sql
CREATE DATABASE mmotors;
```

Modifier le fichier :

```properties
src/main/resources/application.properties
```

Exemple :

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/mmotors
spring.datasource.username=root
spring.datasource.password=password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

# Lancer l’application

## Avec Maven

```bash
mvn spring-boot:run
```

---

# Accès à l’application

Application disponible sur :

```bash
http://localhost:8080
```

---

# Authentification

## Rôles disponibles

### ADMIN

* Gestion des véhicules
* Gestion des dossiers
* Gestion des utilisateurs

### CLIENT

* Consultation des véhicules
* Achat/location
* Suivi des dossiers

---

# Sécurité

Le projet utilise :

* Spring Security
* Authentification sécurisée
* Gestion des rôles
* Protection des routes

---

# Fonctionnalités futures

* Paiement en ligne
* Signature électronique
* Notifications email
* Application mobile
* Tableau de bord statistiques
* Hébergement cloud

---

# Tests

Tests réalisés avec :

* JUnit
* Mockito

Lancer les tests :

```bash
mvn test
```

---

# Auteur

Projet réalisé dans le cadre d’un Bachelor Développeur Web / Java.

---

# Licence

Projet pédagogique — usage académique.
