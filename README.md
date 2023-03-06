# Kafka Auth Microservice

Kafka Auth Microservice is a microservice that provides authentication and authorization capabilities for Kafka-based microservices. This microservice uses Kafka Streams to consume and process messages, and it supports a variety of authentication and authorization mechanisms, including JWT, OAuth2, and LDAP.

## Installation

To install and run this microservice, follow these steps:

1. Clone this repository to your local machine.
2. Install Java 11 or higher.
3. Install Apache Maven 3.6.0 or higher.
4. Set up a Kafka cluster or use an existing one.
5. Configure the microservice by updating the `application.yml` file with the appropriate Kafka cluster and authentication details.
6. Build the project by running `mvn clean package`.
7. Start the microservice by running `java -jar target/kafka-auth-microservice-<version>.jar`.

## Usage

Once the microservice is up and running, you can send requests to it using Kafka messages. The microservice provides several endpoints for authentication and authorization, which are documented in the API documentation.

## Contributing

We welcome contributions to this project. To contribute, please fork this repository, make your changes, and submit a pull request. Be sure to follow our contribution guidelines.

## License

This project is licensed under the Apache License, Version 2.0. See the `LICENSE` file for more details.
