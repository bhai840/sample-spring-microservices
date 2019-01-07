#FROM openjdk
FROM java:openjdk-8u111-jre
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/customer-service.jar customer-service.jar
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
EXPOSE 3333
