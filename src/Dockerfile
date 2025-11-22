# Step 1: Use an official JDK runtime as base image
FROM eclipse-temurin:17-jdk-jammy

# Step 2: Set working directory inside container
WORKDIR /app

# Step 3: Copy the jar file into the container
COPY target/*.jar app.jar

# Step 4: Expose port 8080 to the outside world
EXPOSE 8080

# Step 5: Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]