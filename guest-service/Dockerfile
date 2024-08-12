FROM openjdk:11
WORKDIR /app

# Download the JAR file from the provided URL
COPY guest-room-0.0.1-SNAPSHOT.jar /app
EXPOSE 8080
ENTRYPOINT [ "java", "/app/app.jar" ]
