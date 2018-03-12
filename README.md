# spring-boot-example-app
Example Spring Boot application

Build the app:

    ./gradlew build

Run the application:

    java -jar build/libs/spring-boot-app-0.1.0.jar
    
Check health endpoint:

    curl localhost:8080/actuator/health
    curl localhost:8080/actuator/info

