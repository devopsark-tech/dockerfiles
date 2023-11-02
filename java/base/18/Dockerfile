# Use the official OpenJDK 11 base image from Docker Hub
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy your Java application JAR file to the container
COPY app.jar /app/app.jar

# Define the command to run your Java application
CMD ["java", "-jar", "app.jar"]
