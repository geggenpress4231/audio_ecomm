# Audio Ecommerce Modeling Project

## Overview
This repository contains the source code for an Audio Ecommerce Modeling project. The project employs a microservices architecture, including services such as Product Service, Order Service, Image Service, and a Eureka Service for service registration and discovery.

## Services Description
- **Product Service**: Manages data related to audio products, including ID, name, description, price, image ID, and stock levels.
- **Order Service**: Manages customer orders, capturing details such as customer ID, order date, total amount, and product-specific details.
- **Image Service**: Manages images associated with products, crucial for the product catalog.
- **Eureka Service**: Handles service registration and discovery, facilitating interaction between the microservices.

## Technologies Used
- **Java with Spring Boot**: Framework for creating the microservices.
- **Spring Cloud Netflix Eureka**: Used for service discovery.
- **MySQL**: Database for storing service data.
- **Docker**: Containerization of services.
- **Git**: Version control system used for source code management.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Java JDK 11 or later**: [Download JDK](https://jdk.java.net/)
- **Maven**: [Installing Maven](https://maven.apache.org/install.html)
- **Docker**: [Get Docker](https://docs.docker.com/get-docker/)
- **MySQL**: [Install MySQL](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/)

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/geggenpress4231/audio_ecomm.git
