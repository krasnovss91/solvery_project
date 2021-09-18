FROM adoptopenjdk/openjdk11:jdk-11.0.5_10-alpine

WORKDIR /app

COPY target/spring-boot-microservice-eureka-naming-server-1.0-SNAPSHOT.jar .

CMD ["java", "-jar", "spring-boot-microservice-eureka-naming-server-1.0-SNAPSHOT.jar"]

EXPOSE 8761