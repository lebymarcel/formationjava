# formationjava
Formation sur springboot



## Liens
-https://start.spring.io/

http://www.java2s.com/Tutorials/Java/JPA/0120__JPA_Column_Name.htm

https://www.baeldung.com/jpa-get-auto-generated-id

Liens de configuration des base de données
https://www.baeldung.com/spring-boot-h2-database


## Les dépendances du Projet
Spring Data JPA SQL
Persist data in SQL stores with Java Persistence API using Spring Data and Hibernate.
*********
MySQL Driver SQL
MySQL JDBC and R2DBC driver.
***************
H2 Database SQL
Provides a fast in-memory database that supports JDBC API and R2DBC access, with a small (2mb) footprint. Supports embedded and server modes as well as a browser based console application.
**********************
Rest Repositories WEB
Exposing Spring Data repositories over REST via Spring Data REST.
*************************
Rest Repositories HAL Explorer WEB
Browsing Spring Data REST repositories in your browser.
*********************************
Spring Boot DevTools DEVELOPER TOOLS
Provides fast application restarts, LiveReload, and configurations for enhanced development experience.


*************************************
## Commandes Maven

```
mvn compile ( Pour compiler)
mvn test (Pour lancer les tests)
mvn package (Pour faire le package)
mvn clean compile (Popur nettoyer et recompiler)

```
*****
##  Ligne de commande pour exécuter le projet 

C:\WORKPLACE\FORMATION JAVA\easygescom\target>java -jar easygescom-0.0.1-SNAPSHOT.jar

```
Java -jar +nom du projet 
Voir ci dessous  :
java -jar easygescom-0.0.1-SNAPSHOT.jar

```
## Execution de l'application
apres avoir compiler
mvn package
on lance avaec java-jar
Lorsqu'on a le message : "Tomcat started on port(s): 8080 (http) with context path"
Le projet est donc bon.

Allez sur l'adresse IP :
http; Adresse IP: Port 
Le port utilisé ici est le 8080
http://127.0.0.1:8080/
.
## JPA Repository permet d'appeler les méthodes ci dessous, qui permettent de manipuler les entités
Voir le lien ci dessous.
https://docs.spring.io/spring-data/jpa/docs/current/api/org/springframework/data/jpa/repository/JpaRepository.html

count, delete, deleteAll, deleteAll, deleteAllById, deleteById, existsById, findById, save
Ces méthodes permettent de mettre a jour la base de données et de la manipuler.

## Architecture end to end (Architecture spring boot
0-Serveur Web Tomcat
1-HTML CSS JAVASCRIPT
2-FRAMEWORK thymeleaf https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html
3-Spring mvc : controller (C)
4-Spring services ( Implémentation des règles de gestion)
5-Spring Repository/JPA/ORM
6-Spring entité/JPA/ORM
7-Base de données









