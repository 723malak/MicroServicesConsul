# Étape 1 : Utiliser une image Java légère comme base
FROM openjdk:17-jdk-slim

# Étape 2 : Ajouter l'application jar
COPY target/Client-0.0.1-SNAPSHOT.jar /app/Client-0.0.1-SNAPSHOT.jar

# Étape 3 : Exposer le port de l'application
EXPOSE 8088

# Étape 4 : Commande de lancement de l'application
ENTRYPOINT ["java", "-jar", "/app/Client-0.0.1-SNAPSHOT.jar"]