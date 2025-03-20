# eCommerce website - Microservices architecture
# Overview 
This project is an eCommerce website designed using a microservices architecture. The system is built with Java and Spring Boot, following the Model-View-Controller (MVC) pattern to ensure clean separation of concerns and maintainability. Each microservice is responsible for a specific domain of the application, allowing for scalability and independent development.
# Microservices 
Order Service: (https://github.com/saisasikumard/Order--service)

Description: Handles product data.
Key Features: CRUD operations, secured API calls.
User Service: (https://github.com/saisasikumard/User-Service)

Description: Manages user profiles, user authentication and authorization.
Key Features: OAuth2, JWT tokens.
Payment Service: (https://github.com/saisasikumard/Payment--Service)

Description: Processes payment transactions.
Key Features: Payment gateway integration, transaction history, refunds.
Service Discovery: (https://github.com/saisasikumard/eureka-Service-Registry)

Description: Maintains the list of all servers running a particular microservice.
Key Features: Eureka server, Spring cloud.
API Gateway and Load Balancer: (https://github.com/saisasikumard/Api-Gateway)

Description: Routes the request to corresponding microservice in a load balanced way.
Key Features: Load balancing, Rate limiting, extra layer of authentication.
For any questions or collaboration, feel free to reach out to me at dhavileswarapusaikumar@gmail.com.
