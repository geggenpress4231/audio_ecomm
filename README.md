his repository contains the source code for an Enterprise Application Modeling project, focusing on a microservices architecture. The project is structured into three main services: Product Service, Order Service, and Image Service. Additionally, it incorporates a Eureka Service for service discovery.

Services Description
Product Service: Manages product data including ID, product name, description, price, image ID, and stock level.
Order Service: Handles customer orders, storing customer ID, order date, total amount, and product details.
Image Service: Responsible for managing images related to products, essential for the product catalog.
Technologies Used
Java with Spring Boot
Spring Cloud Netflix Eureka
MySQL (for database)
Docker
Git (for version control)
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
What things you need to install the software and how to install them:

Java JDK 11 or later
Maven
Docker
MySQL
Installing
A step by step series of examples that tell you how to get a development environment running.

Clone the repository
bash
Copy code
git clone https://yourrepositorylink.git
Navigate to each service directory and build the Docker images
bash
Copy code
cd ProductService
docker build -t product-service .
bash
Copy code
cd OrderService
docker build -t order-service .
bash
Copy code
cd ImageService
docker build -t image-service .
bash
Copy code
cd EurekaService
docker build -t eureka-service .
Run the Docker containers
bash
Copy code
docker run -p 8080:8080 product-service
docker run -p 8081:8081 order-service
docker run -p 8082:8082 image-service
docker run -p 8761:8761 eureka-service
Configuring MySQL
Ensure your MySQL instance is set up and running with the necessary databases and user permissions.

Contributions
Param Sureshbhai Gandhi: Focused on setting up the Eureka service and Docker configurations, including building and managing Docker images.
Utsa Rabbani: Worked on developing the Product and Order services, including their respective databases, APIs, and Docker configurations.
