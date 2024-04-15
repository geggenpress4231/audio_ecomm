# Use the official OpenJDK image as a parent image
FROM openjdk:21-slim

# Set the working directory in the container
WORKDIR /app

# Copy the packaged jar file into the container at path /app
COPY target/Order-0.0.1-SNAPSHOT.jar /app/order-server.jar

# Make port 8080 available to the world outside this container
EXPOSE 8080
# Run the jar file
CMD ["java", "-jar", "order-server.jar"]
