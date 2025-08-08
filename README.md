# Product Service

## Description

The `Product Service` is a microservice within the Zalando Lite v2 platform. Its main function is to manage static product information, such as name, description, price, and category. It uses a PostgreSQL database to ensure data integrity and consistency.

## Technologies

-   **Language**: Java 17
-   **Framework**: Spring Boot
-   **Database**: PostgreSQL
-   **Containerization**: Docker

## API Endpoints

| Method | URL | Description |
| :--- | :--- | :--- |
| `POST` | `/api/products` | Creates a new product. |
| `GET` | `/api/products` | Retrieves a list of all products. |

## How to Run

To run this service, make sure you have Docker installed. Navigate to the project's root directory and run the following command to build the Docker image and start the service along with the PostgreSQL database:

```bash
docker-compose up --build