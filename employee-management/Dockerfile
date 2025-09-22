# Use Java 17 runtime
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy jar file (after Maven build)
COPY target/*.jar app.jar

# Run the jar
ENTRYPOINT ["java","-jar","app.jar"]
