# Image officielle Java 17
FROM eclipse-temurin:17-jdk

# Copier le jar Spring Boot
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar

# Exposer le port
EXPOSE 8080

# Lancer l'application
ENTRYPOINT ["java", "-jar", "/app.jar"]
