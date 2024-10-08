FROM openjdk:17-jdk-slim
WORKDIR /app
COPY ./test925-0.0.1-SNAPSHOT.jar /app/app.jar
COPY ./application.properties /app/application.properties
CMD [ "java", "-jar", "/app/app.jar" ]

