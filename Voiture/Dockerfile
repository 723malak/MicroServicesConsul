# Étape 1 : Utiliser une image Java légère comme base
FROM openjdk:17-jdk-slim

# Étape 2 : Ajouter l'application jar
COPY target/Voiture-0.0.1-SNAPSHOT.jar /app/Voiture-0.0.1-SNAPSHOT.jar

# Étape 3 : Exposer le port de l'application
EXPOSE 8089

# Étape 4 : Commande de lancement de l'application
ENTRYPOINT ["java", "-jar", "/app/Voiture-0.0.1-SNAPSHOT.jar"]