FROM eclipse-temurin:17-jdk-alpine

COPY target/development-0.0.1-SNAPSHOT.jar development.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","development.jar"]