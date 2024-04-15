# Use the official OpenJDK image as a parent image
FROM openjdk:21-slim

# Set the working directory in the container
WORKDIR /app

# Copy the packaged jar file into the container at path /app
COPY target/eureka-server-0.0.1-SNAPSHOT.jar /app/eureka-server.jar

# Make port 8761 available to the world outside this container
EXPOSE 8761

# Run the jar file
CMD ["java", "-jar", "eureka-server.jar"]
