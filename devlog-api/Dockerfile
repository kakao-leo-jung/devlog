FROM openjdk:11-jre-slim

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} devlog.jar

ENTRYPOINT ["java", "-jar", "/devlog.jar"]

