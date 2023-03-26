FROM gradle:jdk8

WORKDIR /app

COPY users-microservice/build/libs/*.jar users-microservice.jar
CMD ["java", "-jar", "users-microservice.jar"]