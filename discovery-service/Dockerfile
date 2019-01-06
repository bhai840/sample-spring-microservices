//FROM openjdk
FROM alpine-java:base
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/discovery-service.jar discovery-service.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/discovery-service.jar"]
//CMD ["-start"]
EXPOSE 8761
