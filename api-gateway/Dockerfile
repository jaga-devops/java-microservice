FROM ubuntu 
RUN apt-get update
RUN apt-get install openjdk-17-jdk
COPY ./target/api-gateway-0.0.1-SNAPSHOT.jar /app/api-gateway-0.0.1-SNAPSHOT.jar
RUN java -jar target/api-gateway-0.0.1-SNAPSHOT.jar
