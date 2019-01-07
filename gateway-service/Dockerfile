#FROM openjdk
FROM java:openjdk-8u111-jre
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/gateway-service.jar gateway-service.jar
ENTRYPOINT ["java", "-jar", "/gateway-service.jar"]
EXPOSE 8765
