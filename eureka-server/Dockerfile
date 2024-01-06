FROM openjdk:11

COPY ./target/eureka-server-1.jar /app/eureka-server-1.jar
 
WORKDIR /app

RUN java --illegal-access=permit -jar /app/eureka-server-1.jar
