FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

COPY target/spring-boot-web.jar app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
