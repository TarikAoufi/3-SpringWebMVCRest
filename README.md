# 3-SpringWebMVCRest
Maven + Spring MVC+ Spring Data JPA + Spring Test + REST + Hibernate + JUnit + MySQL

Dans ce Demo, nous utilisons:
  - Spring-webmvc
  - Spring-data-jpa: Pour simplifier le développement de la couche DAO
  - Le contrôleur "PersonneRestController" pour tester le WebService avec REST,  et un consomateur de ce service dans le projet 
	  SpringRESTClient (le main: Runtime)
  - Un package exception, qui contient la classe PersonneNotFoundException, pour gérer les exceptions  générées par REST
	  et le message à afficher lors de ce traitement dans le package dto: Class JsonError.
  - Un test unitaire de la couche service.
