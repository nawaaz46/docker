FROM openjdk.11
WORKDIR /app
EXPOSE 8088
COPY target/docker-0.0.1-SNAPSHOT.jar /app/app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]