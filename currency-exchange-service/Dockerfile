FROM java:8
ARG JAR_FILE=target/currency-exchange-service-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} currency-exchange-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","currency-exchange-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8080

