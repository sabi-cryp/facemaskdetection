# Utilisez une image de base qui convient à votre application
FROM openjdk:8-jdk-alpine

# Créez le répertoire de travail
WORKDIR /app

# Copiez tous les fichiers nécessaires dans le conteneur
COPY . .

# Exécutez les commandes de build ou d'installation (adaptez en fonction de votre projet)
RUN ./gradlew build

# Spécifiez la commande de démarrage de votre application
CMD ["java", "-jar", "build/libs/votre_application.jar"]
