
# Step 1: Base image (Java runtime)
FROM openjdk:17-jdk-slim

# Step 2: Copy built JAR file
COPY build/libs/*.jar app.jar

# Step 3: Run application
ENTRYPOINT ["java", "-jar", "/app.jar"]
