# Use official OpenJDK base image
FROM openjdk:17

# Set environment variable for working directory
WORKDIR /app

# Copy the JAR file into the container
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
