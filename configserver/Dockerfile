#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim as build

#Information around who maintains the image
MAINTAINER abhishek

# Add the application's jar to the container
COPY target/configServer-0.0.1-SNAPSHOT.jar configServer-0.0.1-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java","-jar","/configServer-0.0.1-SNAPSHOT.jar"]
