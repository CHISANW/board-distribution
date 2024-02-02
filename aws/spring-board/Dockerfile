FROM openjdk:11-jdk-slim

WORKDIR /app

COPY ./jar/*.jar /app/board.jar

ENTRYPOINT ["java", "-jar","board.jar"]