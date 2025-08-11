
Investment Management - Spring Boot Project (Scaffold)
----------------------------------------------------

What's included:
- Simple Spring Boot (Maven) scaffold with JPA entities and repositories.
- H2 in-memory DB for easy local testing.
- Entities: Advisor, Client, Portfolio, Security, PortfolioSecurity.
- Repositories for basic CRUD operations.

How to run:
1. Install Java 11+ and Maven.
2. In project root (where pom.xml is), run:
   mvn spring-boot:run
3. Open H2 console at http://localhost:8080/h2-console (JDBC URL: jdbc:h2:mem:investdb)

Files:
- src/main/java/com/example/investment/InvestmentManagementApplication.java
- src/main/java/com/example/investment/entity/*.java
- src/main/java/com/example/investment/repository/*.java
- src/main/resources/application.properties
- pom.xml

Notes for Forage submission:
- This scaffold implements the data model in JPA. You can extend controllers/services as needed.
- If you want, I can add example REST controllers and sample data loader.
