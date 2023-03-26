FROM gradle:jdk8

WORKDIR /app

COPY api-microservice/build/libs/*.jar api-microservice.jar
CMD ["java", "-jar", "api-microservice.jar"]