# E-Commerce App

## <u>Business Logic:</u>

- An ecommerce app allows customers to shop online, browse product catalogs, add items to a cart, and
  complete purchases. It also provides payment processing, shipping, and order management capabilities.
- A microservice based demo project using spring boot and spring cloud that includes the main components of microservice
  projects.

## <u>Project Components and services:</u>

- **Eureka Server**: Eureka Server is a service registry that plays a central role in the automatic detection of devices
  and services on a network.
- **API Gateway**: manages incoming requests and routes them based on key factors such as request path, headers, and
  query parameters, among others.
- **Config Server**: is a client/server approach for storing and serving distributed configurations across multiple
  applications and environments.
- **Spring Admin Server**: is a web application, used for managing and monitoring Spring Boot applications.
- **Customer Service**: The service allows admins to manage the customers data using the below APIs:
    * create customer
    * update customer
    * delete customer
    * find customer by ID
    * find customers page
    * check if customer exists
- **Product service**: The service allows customers to browse product catalogs, and purchase products, and allows admins
  to manage products by the below APIs:
    * create product
    * update product
    * delete product
    * find product by ID
    * find products page
    * purchase products
- **Order service**: The service allows customers to create orders and make purchases.
    * create order
    * find order by ID
    * find customer orders page
- **Payment Service**: The service allows customers to do the payment.
    * do payment
- **Notification Service**: is a service to consume and process the received notification messages.
- **Mail Service**: is a service, used for sending the notification mail to the customers.

## <u>Used Technologies & Tools:</u>

- Spring boot
- Spring JPA
- Spring validation
- Spring cloud
- Netflix eureka client and server
- spring cloud gateway and load balancer
- OpenFeign
- Liquibase
- mapstruct
- Lombok
- ControllerAdvice
- Spring cloud Zipkin
- Postgres DB
- Mongo DB
- Keycloak
- Kafka and zookeeper
- Docker
- Docker Compose
- tomcat Server
- IntelliJ IDE
- Mongo express
- DBeaver

## <u>Repo:</u>

- [E-Commerce App](https://github.com/e-commerce-app-2024)

