![](https://github.com/Lylio/image-repo/blob/master/logos/quarkus.png?raw=true)
![](https://github.com/Lylio/image-repo/blob/master/logos/flyway.png?raw=true)

# Multitenancy

### Description
A Quarkus application demonstrating multitenancy functionality with Flyway.

### Tech Stack
- Quarkus (JDK 11)
- Flyway
- Maven

### Setup & Launch

#### Database
Flyway expects a PostgreSQL database named 'quarkus_test' to have already been created before the app boots. At the psql shell, 
simply execute `CREATE DATABASE quarkus_test`.

#### Quarkus Backend Launch
1. Run `mvn quarkus:dev` in the root directory to start the Quarkus application
2. Navigate to http://localhost:8080/index.html
3. Flyway can be instructed to 'clean' and 'build' from the Quarkus dev UI at http://localhost:8080/q/dev/

<br/>

#### Acknowledgments
Based on the Quarkus.io article [USING HIBERNATE ORM AND JPA : Multitenancy](https://quarkus.io/guides/hibernate-orm#multitenancy).