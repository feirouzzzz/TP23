# Image Java légère
FROM eclipse-temurin:17-jre-alpine

# Dossier de travail
WORKDIR /app

# Copier le jar
COPY target/*.jar app.jar

# Port Eureka
EXPOSE 8761

# Lancement
ENTRYPOINT ["java", "-jar", "app.jar"]
