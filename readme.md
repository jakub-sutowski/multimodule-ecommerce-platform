### Multimodule E-Commerce Platform

A comprehensive e-commerce platform consisting of three modules: Bank, Shop, and Token. The Bank module handles payments, the Shop module manages the online store, and the Token module deals with user authentication and token generation.

### Technologies Used

- Java
- Spring Boot
- PostgreSQL
- Docker

### Running the Project

To run the project, follow these steps:

1. **Configure Docker Compose**

   Ensure that you have Docker installed on your system. Then, use the following command:

   ```bash
   docker-compose up -d
   ```

   This command will start all three modules (Bank, Shop, and Token) along with their respective PostgreSQL databases in Docker containers.

2. **Accessing the Applications**

    - Bank Module: [http://localhost:8080/bank](http://localhost:8080/bank)
    - Shop Module: [http://localhost:8080/shop](http://localhost:8080/shop)
    - Token Module: [http://localhost:8080/token](http://localhost:8080/token)

3. **Swagger API Documentation**

   Each module has its Swagger API documentation accessible at the following URLs:

    - Bank Module: [http://localhost:8080/bank/swagger-ui.html](http://localhost:8080/bank/swagger-ui.html)
    - Shop Module: [http://localhost:8080/shop/swagger-ui.html](http://localhost:8080/shop/swagger-ui.html)
    - Token Module: [http://localhost:8080/token/swagger-ui.html](http://localhost:8080/token/swagger-ui.html)

### Project Structure

The project structure includes the following components:

- **bank**: Source code for the Bank module.
- **shop**: Source code for the Shop module.
- **token**: Source code for the Token module.
- **docker-compose.yml**: Docker Compose configuration for running the modules and their databases in containers.
- **application.properties**: Configuration properties for local environments.
- **application-docker.properties**: Configuration properties for Docker environments.

### Building and Running Locally

If you want to build and run the modules locally without Docker, make sure you have Java installed.

The applications will be accessible at the following URLs:

- Bank Module: [http://localhost:8081](http://localhost:8081)
- Shop Module: [http://localhost:8080](http://localhost:8080)
- Token Module: [http://localhost:8082](http://localhost:8082)

### Notes

Make sure to adjust configurations, such as database URLs or application properties, according to your specific requirements in the appropriate property files for each module.