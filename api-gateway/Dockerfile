FROM ubuntu 
RUN apt-get update
RUN apt-get -y install openjdk-8-jdk
COPY ./target/api-gateway-0.0.1-SNAPSHOT.jar /app/api-gateway-0.0.1-SNAPSHOT.jar
WORKDIR /app
RUN java -jar /app/api-gateway-0.0.1-SNAPSHOT.jar
