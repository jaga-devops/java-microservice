FROM maven:3.8.4-jdk-11

COPY ./target/api-gateway-0.0.1-SNAPSHOT.jar /app/api-gateway-0.0.1-SNAPSHOT.jar
 
WORKDIR /app

CMD java -jar /app/api-gateway-0.0.1-SNAPSHOT.jar
