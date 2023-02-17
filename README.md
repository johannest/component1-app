# Hilla-React micro-frontend example: component1-app

This is component1-app of the Hilla-React micro-frontend example. This can be developed and run independently of the `main-app`. This module shares data with `main-app` from main-app's a React Context to the Props of app's [Component1ReactView.tsx](frontend%2Fviews%2FComponent1ReactView.tsx)'s single TextField. This is done purely for demonstrating the use of React Context and Props for sharing the state and is not something that you would likely do in real life in this exact form.

This example project is shared in its own GitHub repository. See also the example project using multi-module Maven approach and single GitHub repository: 

## Running the application

The project is a standard Maven project. To run it from the command line,
type `mvnw` (Windows), or `./mvnw` (Mac & Linux), then open
http://localhost:8080 in your browser.


**Or use directly Spring Boot Maven plugin: `mvn spring-boot:run`.**

You can also import the project to your IDE of choice as you would with any
Maven project.
