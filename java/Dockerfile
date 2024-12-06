FROM maven:3.8.6-jdk-8 AS build

LABEL maintainer="Maho"

WORKDIR /app

COPY pom.xml pom.xml
COPY src src

RUN mvn clean package -DskipTests


FROM openjdk:8-jdk-alpine

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY --from=build /app/target/java-0.0.1-SNAPSHOT.jar .

EXPOSE 8448

CMD ["java", "-jar", "java-0.0.1-SNAPSHOT.jar"]
