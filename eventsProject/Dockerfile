# Utilisez une image de base qui prend en charge Java 8
FROM openjdk:8
EXPOSE 8089

# Copiez le jar de votre application dans le conteneur
ADD target/eventsProject-SNAPSHOT-01.jar /eventsProject.jar

ENTRYPOINT ["java","-jar","/eventsProject.jar"]