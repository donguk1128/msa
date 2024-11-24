FROM openjdk:17-jdk-slim

EXPOSE 8888

COPY target/config-server.jar /config-server.jar

RUN mkdir -p /server/config

ENTRYPOINT ["java", "-jar", "/config-server.jar"]
