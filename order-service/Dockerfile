FROM openjdk:17-ea-11-jdk-slim
VOLUME /tmp
COPY target/order-service-1.0.jar OrderSerivce.jar
ENTRYPOINT ["java","-jar","OrderSerivce.jar"]