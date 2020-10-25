# AMQP
Spring boot and Rabbit MQ

# 1. Overview
We'll explore message-based communication over AMQP using the Spring framework.In this project you will see how to send and receive message with RabbitMQ.
# 2. Message-Based Communication
One way to communicating between applications is messaging . Producers and consumers of messages are decoupled by an intermediate messaging layer known as a message broker
# 3. AMQP – Advanced Message Queuing Protocol
A simple define for AMQP is an open standard wire specification for asynchronous message communication.
# 4. Setup a Rabbitmq in pom file
In order to add the spring-amqp and spring-rabbit modules to our project, we add the spring-boot-starter-amqp dependency to our pom.xml:

    <dependencies>
          <dependency>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-amqp</artifactId>
              <version>2.2.2.RELEASE</version>
          </dependency>
      </dependencies>


# 5. Setup a AMQP in pom file
    <dependency>
        <groupId>com.rabbitmq</groupId>
        <artifactId>amqp-client</artifactId>
        <version>5.8.0</version>
      </dependency>

# 7. Conclusion
In this tutorial, we lerned how to send message over AMQP protocol and RabbitMQ between applications.
