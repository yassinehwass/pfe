FROM maven:3.8.5-openjdk-17

# maven:3.8.5-openjdk-17 image pour le build 

COPY springboot-backend-0.0.1-SNAPSHOT.jar springboot-backend.jar
ADD application.properties application.properties

ENTRYPOINT ["java","-Dspring.config.location=application.properties","-jar","/springboot-backend.jar"]
