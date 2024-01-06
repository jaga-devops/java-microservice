FROM openjdk:8

COPY ./target/eureka-server-1.jar /app/eureka-server-1.jar
 
WORKDIR /app

CMD java --illegal-access=permit -jar /app/eureka-server-1.jar
