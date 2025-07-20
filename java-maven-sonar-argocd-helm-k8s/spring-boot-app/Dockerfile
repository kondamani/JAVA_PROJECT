# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM maven:3.9.4-eclipse-temurin-17-alpine

# Simply the artifact pathhh
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
