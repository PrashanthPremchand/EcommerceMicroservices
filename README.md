# EcommerceMicroservices

Overview: Developed a microservices-based application with Spring Boot, leveraging modular services for scalability and reliability.
Key Components:
API Gateway: Centralized entry point for routing requests and handling authentication.
Auth Server: Managed user authentication and authorization, secured with OAuth2 or similar protocols.
Core Microservices:
  Product Service: Managed product data using MongoDB.
  Order Service: Handled orders with asynchronous communication via Kafka and synchronous interactions with other services.
  Inventory Service: Managed inventory data stored in MySQL.
  Notification Service: Sent notifications leveraging event-driven architecture.
Resilience4j: Implemented fault tolerance (e.g., circuit breakers, retries).
Service Discovery: Used Eureka for dynamic service registration and discovery.
Data Storage: MongoDB and MySQL databases for respective services.
Observability & Monitoring: Integrated OpenTelemetry, Prometheus, Grafana Loki, and Grafana Tempo for distributed tracing, logging, and metrics visualization.
Deployment: Dockerized services orchestrated with Kubernetes for high availability and scalability.

API-gateway - https://github.com/PrashanthPremchand/EcommerceAPIGateway
Product-Service - https://github.com/PrashanthPremchand/ProductService
Order-Service - https://github.com/PrashanthPremchand/OrderService
Inventory-Service - 
Notification-Service - 
