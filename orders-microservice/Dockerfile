FROM gradle:jdk8

WORKDIR /app

COPY orders-microservice/build/libs/*.jar orders-microservice.jar
CMD ["java", "-jar", "orders-microservice.jar"]