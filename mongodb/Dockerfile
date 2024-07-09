# FROM maven:3.8.2-jdk-8 # for Java 8
FROM ubuntu:22.04

WORKDIR /mongodb
COPY . .
RUN mvn clean install

CMD mvn spring-boot:run