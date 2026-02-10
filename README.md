Très bien.
Voici le **README sans emoji**, propre et académique.

---

# M1 UBO – Spring Boot Testing App

## Description

Ce projet est une application **Spring Boot** réalisée dans le cadre du **Master 1 Informatique à l’Université de Bretagne Occidentale (UBO)**.
Il a pour objectif de mettre en pratique les **tests en Spring Boot**, notamment les tests unitaires et les tests d’intégration.

## Technologies utilisées

* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* JUnit
* Mockito
* Maven
* H2 (base de données en mémoire)

## Structure du projet



## Récupération du projet

Cloner le dépôt GitHub :

```bash
git clone https://github.com/Prakkkmak/M1-UBO-Spring-Boot-Testing-App.git
cd M1-UBO-Spring-Boot-Testing-App
```

## Configuration

La configuration de l’application est définie dans le fichier `application.properties`.

Exemple :

```properties
server.port=8080
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driver-class-name=org.h2.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## Lancement du projet

### Avec Maven

```bash
mvn spring-boot:run
```

### Exécution des tests

```bash
mvn test
```

## Accès à l’application

* Application : [http://localhost:8080](http://localhost:8080)
* Console H2 : [http://localhost:8080/h2-console](http://localhost:8080/h2-console)

## Tests

Le projet contient :

* des tests unitaires ;
* des tests d’intégration ;
* l’utilisation de Mockito pour le mock des dépendances.

## Contexte académique

Projet réalisé dans le cadre du **Master 1 Informatique – Université de Bretagne Occidentale**.

## Auteur

* Clément

