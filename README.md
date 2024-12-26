# EcommerceMicroservices

Overview: Developed a microservices-based application with Spring Boot, leveraging modular services for scalability and reliability.<br />
Key Components:<br />
API Gateway: Centralized entry point for routing requests and handling authentication.<br />
Auth Server: Managed user authentication and authorization, secured with OAuth2 or similar protocols.<br />
Core Microservices:<br />
  Product Service: Managed product data using MongoDB.<br />
  Order Service: Handled orders with asynchronous communication via Kafka and synchronous interactions with other services.<br />
  Inventory Service: Managed inventory data stored in MySQL.<br />
  Notification Service: Sent notifications leveraging event-driven architecture.<br />
Resilience4j: Implemented fault tolerance (e.g., circuit breakers, retries).<br />
Service Discovery: Used Eureka for dynamic service registration and discovery.<br />
Data Storage: MongoDB and MySQL databases for respective services.<br />
Observability & Monitoring: Integrated OpenTelemetry, Prometheus, Grafana Loki, and Grafana Tempo for distributed tracing, logging, and metrics visualization.<br />
Deployment: Dockerized services orchestrated with Kubernetes for high availability and scalability.<br />
<br />
API-gateway - https://github.com/PrashanthPremchand/EcommerceAPIGateway<br />
Product-Service - https://github.com/PrashanthPremchand/ProductService<br />
Order-Service - https://github.com/PrashanthPremchand/OrderService<br />
Inventory-Service - https://github.com/PrashanthPremchand/InventoryService<br />
Notification-Service - https://github.com/PrashanthPremchand/NotificationService<br />
