# CreditInsightTool
A microservices prototype built with Spring Boot demonstrating key integrations like Redis caching, Kafka messaging, OAuth2 security, Log4j2 & Splunk logging, and API routing with Spring Cloud Gateway.

---

## Repository

[https://github.com/rushithalakshmi/CreditInsightTool](https://github.com/rushithalakshmi/CreditInsightTool)

---

## Services Overview

- **CreditScoringServiceMS**  
  Implements credit score logic, Redis caching, Kafka notifications, email alerts, and logging.
- **UserManagementMS**  
  Manages user registration and login with OAuth2 and JWT authentication.
- **SpringCloudGatewayMS**  
  API gateway for routing requests, applying security, and handling CORS.

---

## Key Features

- Redis caching for fast credit score retrieval  
- Kafka for asynchronous credit score update notifications  
- Email notifications triggered by Kafka events  
- Log4j2 and Splunk integration for advanced logging  
- OAuth2-based security for user authentication  
- RESTful inter-service communication using Spring WebFlux WebClient  
- API Gateway to secure and route client requests

---

## Getting Started

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/rushithalakshmi/CreditInsightTool.git
