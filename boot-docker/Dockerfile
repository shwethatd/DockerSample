FROM openjdk:8
ADD target/boot-docker.jar boot-docker.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar", "boot-docker.jar"]