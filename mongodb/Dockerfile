FROM maven:3.8-openjdk-17
#FROM ubuntu:22.04

WORKDIR /mongodb
COPY . .
RUN mvn clean install

CMD mvn spring-boot:run

EXPOSE 8081