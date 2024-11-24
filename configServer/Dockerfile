FROM openjdk:17-jdk-slim

EXPOSE 8888

COPY build/libs/configServer-0.0.1.jar /config-server.jar

RUN mkdir -p /server/config

ENTRYPOINT ["java", "-jar", "/config-server.jar"]
