FROM openjdk:8-jre


ADD ./target/ts-order-service-1.0.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/ts-order-service-1.0.jar"]
#CMD java $JAVA_OPTIONS -jar /app/ts-order-service-1.0.jar

EXPOSE 12031