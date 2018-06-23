FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/account-service.jar account-service.jar
VOLUME ["/var/run/docker.sock"]
ENTRYPOINT ["java", "-jar", "/account-service.jar"]
EXPOSE 2222
