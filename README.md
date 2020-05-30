# kafka-spring-boot
Sample application of kafka-spring-boot to publish and consume message from spring-boot application to kafka topic

## Starting up Kafka

To start up Kafka and Zookeeper containers, just run docker-compose up from the folder where this file lives.

$ docker-compose up -d

Starting kafka-example_zookeeper_1 ... done

Starting kafka-example_kafka_1     ... done


## Sending messages with Spring Boot and Kafka

$ mvn spring-boot:run


Invoking the endpoint

$ curl localhost:8080/hello
