FROM openjdk:8-jre


ADD ./target/ts-seat-service-1.0.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/ts-seat-service-1.0.jar"]

EXPOSE 18898