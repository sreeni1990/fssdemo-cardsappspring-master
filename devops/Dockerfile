FROM openjdk:8-jre-alpine

USER root

ADD ./target/*.jar /opt/cardsappspring-1.0.0.jar
CMD ["java", "-Xmx200m", "-jar", "/opt/cardsappspring-1.0.0.jar"]

EXPOSE 8080
