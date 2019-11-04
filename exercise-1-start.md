# Exercise 1

## Goal

* Build A Spring Boot 2 Micro Service that expose a REST API on the root and return a 
Fortune Cookie text
* Deploy the Micro Service to Cloud Foundry.

## Steps 

* Go to [https://start.spring.io](https://start.spring.io)
* Create a (Maven) Spring Boot 2 project with starters `Web` and `Actuator` (io.pivotal.workshop.workshopfortuneservice, workshop-fortune-service)
* Select the 2.1.9 version of Spring Boot as the 2.2.0 version has breaking changes for this workshop.
* Download the project and open it in your favourite IDE
* Introduce a ‘Fortune Cookie’ controller (`@RestController`, `@GetMapping`) that returns a simple message
* Build the project using Maven and run it locally first
* Call the REST endpoint from the browser or curl to load the static Fortune text
* If the application is working fine push the application to Cloud Foundry (login required)
* Call the REST endpoint of the deployed application from the browser or curl to load the static Fortune text
