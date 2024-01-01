FROM openjdk:11-jdk-slim

# CMD 예제

WORKDIR /app

COPY build/aws-v3-0.0.3.jar ./application.jar

ENTRYPOINT ["java", "-jar", "-Dspring.profiles.active=dev", "application.jar"]

CMD ["--server.port=3000"]