#FROM openjdk
#FROM alpine:3.8
From java:openjdk-8u111-jre
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/discovery-service.jar discovery-service.jar
#ENTRYPOINT ["/usr/bin/java"]
CMD ["java", "-jar", "/discovery-service.jar"]
#CMD ["-start"]
EXPOSE 8761
