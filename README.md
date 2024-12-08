# zeta assignment

A RESTful API written in Go for managing products. It integrates with PostgreSQL for storage, Redis for caching, RabbitMQ for asynchronous image processing, and provides structured logging with `logrus`.

## Architecture Overview

This backend system is designed with scalability, performance, and fault tolerance in mind. It consists of:

- **PostgreSQL** for data persistence.
- **Redis** for caching product data.
- **RabbitMQ** for asynchronous image processing.
- **Structured logging** with `logrus`.

### Key Endpoints

- **POST /products**: Creates a new product.
- **GET /products/:id**: Fetches product details by ID.
- **GET /products**: Fetches products for a specific user, with filtering options.

### Setup Instructions

#### 1. Clone the repository:
```bash
git clone https://github.com/ohhkmaddy/zocket-assignment.git 

