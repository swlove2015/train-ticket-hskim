FROM openjdk:8-jre


ADD ./target/ts-security-service-1.0.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/ts-security-service-1.0.jar"]

EXPOSE 11188