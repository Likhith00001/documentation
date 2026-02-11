Spring boot project 

first we need to download the project maven file from https://start.spring.io/

Project: Maven
Language: Java
Spring Boot: (default latest)
Group: com.likhith
Artifact: demo
Packaging: Jar
Java: 17 (or your version)
Add Dependency:
Spring Web
Click → Generate

then go to main project file 

run mvn spring-boot:run or mvnw spring-boot:run

once port setup then test port in localhost:8080/

then create the file in same path then inside file
@restControllar is an class inbuilt in spring that call the spring to exucute the class 

@getmapping is the class which map the id to get details from the server which create the path to the server
