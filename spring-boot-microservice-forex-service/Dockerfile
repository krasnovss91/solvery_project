FROM adoptopenjdk/openjdk11:jdk-11.0.5_10-alpine

WORKDIR /app

COPY target/spring-boot-microservice-forex-service-1.0-SNAPSHOT.jar .

ENV PORT 8080

CMD ["java","-jar","spring-boot-microservice-forex-service-1.0-SNAPSHOT.jar"]

EXPOSE ${PORT}