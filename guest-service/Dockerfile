FROM openjdk:11
WORKDIR /app

# Download the JAR file from the provided URL
RUN apt-get update && apt-get install -y curl && \
    curl -L -o app.jar "https://dev.azure.com/kishanhanumante59/_apis/resources/Containers/33100498/drop?itemPath=drop%2Fguest-service%2Ftarget%2Fguest-room-0.0.1-SNAPSHOT.jar"

EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "/app/app.jar" ]
