# Simple Bank Backend Service

This project is a backend system for a simple banking application. The system is designed and developed using **Golang**, **PostgreSQL**, **Docker**, and **Kubernetes**, with a focus on scalability, security, and reliability. It provides RESTful APIs for managing bank accounts, recording transactions, and facilitating secure money transfers.

## Key Features

1. **Account Management**:
   - Create and manage bank accounts with attributes such as owner’s name, balance, and currency.
   - Maintain accurate records of all account balance changes.

2. **Transactional Integrity**:
   - Perform secure money transfers between accounts using database transactions.
   - Ensure atomicity, so either all updates succeed or none are applied.

3. **API Development**:
   - Build RESTful APIs using the **Gin framework**, secured with **JWT** and **PASETO** tokens.
   - Include robust error handling and user authentication.

4. **Testing and Coverage**:
   - Write comprehensive unit tests with mocking for high coverage.
   - Use interfaces to create a more modular and testable codebase.

5. **Asynchronous Processing**:
   - Implement background workers for processing tasks such as sending emails.
   - Use **Redis** and **Asynq** as the message queue system.

6. **Deployment and Automation**:
   - Create a minimal **Docker** image for deployment.
   - Use **Docker Compose** for local development and set up a Kubernetes cluster on AWS for production.
   - Automate CI/CD pipelines with **GitHub Actions** for building and deploying the application.

7. **gRPC Integration**:
   - Extend the service with **gRPC APIs** and **gRPC Gateway** for dual support of HTTP and gRPC requests.
   - Embed Swagger documentation for easy API reference.

8. **Domain and TLS Configuration**:
   - Register and configure a domain name.
   - Enable HTTPS with **Let's Encrypt** for secure traffic routing, including automatic certificate renewal.

9. **Scalability and Security**:
   - Implement advanced isolation levels to avoid deadlocks and ensure database consistency.
   - Use structured logging for better observability and maintainability.

## Tools and Technologies

- **Programming Language**: Go (Golang)
- **Database**: PostgreSQL
- **Frameworks**: Gin, gRPC
- **Containerization**: Docker, Kubernetes
- **Message Queue**: Redis, Asynq
- **CI/CD**: GitHub Actions
- **Others**: Swagger, Let’s Encrypt

## How It Works

1. **Account Creation**: Allows users to create accounts and manage their details.
2. **Transaction Logging**: Tracks every deposit, withdrawal, or transfer operation.
3. **Money Transfers**: Processes inter-account transfers securely within a single transaction to ensure data consistency.

## Setup and Deployment

1. Clone the repository:  
   ```bash
   git clone h# Simple Bank Backend Service

This project is a backend system for a simple banking application. The system is designed and developed using **Golang**, **PostgreSQL**, **Docker**, and **Kubernetes**, with a focus on scalability, security, and reliability. It provides RESTful APIs for managing bank accounts, recording transactions, and facilitating secure money transfers.

## Key Features

1. **Account Management**:
   - Create and manage bank accounts with attributes such as owner’s name, balance, and currency.
   - Maintain accurate records of all account balance changes.

2. **Transactional Integrity**:
   - Perform secure money transfers between accounts using database transactions.
   - Ensure atomicity, so either all updates succeed or none are applied.

3. **API Development**:
   - Build RESTful APIs using the **Gin framework**, secured with **JWT** and **PASETO** tokens.
   - Include robust error handling and user authentication.

4. **Testing and Coverage**:
   - Write comprehensive unit tests with mocking for high coverage.
   - Use interfaces to create a more modular and testable codebase.

5. **Asynchronous Processing**:
   - Implement background workers for processing tasks such as sending emails.
   - Use **Redis** and **Asynq** as the message queue system.

6. **Deployment and Automation**:
   - Create a minimal **Docker** image for deployment.
   - Use **Docker Compose** for local development and set up a Kubernetes cluster on AWS for production.
   - Automate CI/CD pipelines with **GitHub Actions** for building and deploying the application.

7. **gRPC Integration**:
   - Extend the service with **gRPC APIs** and **gRPC Gateway** for dual support of HTTP and gRPC requests.
   - Embed Swagger documentation for easy API reference.

8. **Domain and TLS Configuration**:
   - Register and configure a domain name.
   - Enable HTTPS with **Let's Encrypt** for secure traffic routing, including automatic certificate renewal.

9. **Scalability and Security**:
   - Implement advanced isolation levels to avoid deadlocks and ensure database consistency.
   - Use structured logging for better observability and maintainability.

## Tools and Technologies

- **Programming Language**: Go (Golang)
- **Database**: PostgreSQL
- **Frameworks**: Gin, gRPC
- **Containerization**: Docker, Kubernetes
- **Message Queue**: Redis, Asynq
- **CI/CD**: GitHub Actions
- **Others**: Swagger, Let’s Encrypt

## How It Works

1. **Account Creation**: Allows users to create accounts and manage their details.
2. **Transaction Logging**: Tracks every deposit, withdrawal, or transfer operation.
3. **Money Transfers**: Processes inter-account transfers securely within a single transaction to ensure data consistency.

## Setup and Deployment

1. Clone the repository:  
   ```bash
   git clone https://https://github.com/hesammosaffa/simple_bank
   cd simple-bank
   ```
2. Start the application locally using Docker Compose:
   ```bash
   docker-compose up
   ```
3. Access the APIs locally via the provided Swagger documentation.

## Roadmap

Future enhancements may include:
- Integration with external payment gateways.
- Additional reports and analytics features.
- Enhanced monitoring and alerting systems.

## Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

   cd simple-bank
   ```
2. Start the application locally using Docker Compose:
   ```bash
   docker-compose up
   ```
3. Access the APIs locally via the provided Swagger documentation.

## Roadmap

Future enhancements may include:
- Integration with external payment gateways.
- Additional reports and analytics features.
- Enhanced monitoring and alerting systems.

## Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. For major changes, open an issue first to discuss what you would like to change.
