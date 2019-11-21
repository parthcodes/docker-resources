FROM openjdk:8-jdk-alpine

LABEL maintainer="patel.parth200@gmail.com"

WORKDIR /tmp
EXPOSE 8080
ADD target/gs-spring-boot-0.1.0.jar .
RUN ls 
CMD java -jar gs-spring-boot-0.1.0.jar
