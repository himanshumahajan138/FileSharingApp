# Use an official Java runtime as the base image
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy your JAR file into the container
COPY fileSharingManagement-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your application uses
EXPOSE 8080

# Run the JAR file
CMD ["java", "-jar", "app.jar"]
