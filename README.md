# RabbitMQSimple by Jules

## Overview

RabbitMQSimple is a microservices architecture project using RabbitMQ as the message broker, developed with JavaScript and Node.js. This project demonstrates how to create scalable and efficient microservices that communicate asynchronously, ideal for distributed systems.

## Features

- **Message Queue Implementation**: Utilizes RabbitMQ to manage message queues.
- **Asynchronous Communication**: Allows for publishing and consuming messages in a streamlined manner.
- **Node.js Platform**: Built with JavaScript using Node.js, ensuring fast and reliable performance.
- **Dockerized Application**: Easily deployable using Docker for seamless integration and management.

## Docker

The project image is available on Docker Hub. Pull the image with the following command:

```bash
docker pull julescruz10015482/rabbitmqsimple-rabbitmq:latest
```

## Usage
To run the application, follow these steps:

- Start Docker: Ensure Docker is running on your system.

- Run Docker Compose: In the rabbitmq-nodejs-messaging-example directory, execute:

    ```docker-compose up -d```

-   Access RabbitMQ: Open your browser and navigate to http://localhost:15672 to access the RabbitMQ management interface.

    Default Credentials:

        Username: rabbitmq
        Password: rabbitmq

- Run the Consumer and Producer:

    Consumer:
        
        cd consumer
        npm run start


    Producer:


        cd ../producer
        npm run start


- Change the message anytime by updating index.js on Producer
