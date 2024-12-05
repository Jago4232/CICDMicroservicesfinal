FROM openjdk:17
WORKDIR /app
COPY ./target/MicroserviceWorkers-1.0.0.jar Workers.jar
EXPOSE 8082
ENTRYPOINT [ "java","-jar","client.jar" ]