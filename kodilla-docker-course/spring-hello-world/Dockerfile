FROM gradle:7.1.0-jdk11

WORKDIR /usr/src/app

COPY . .

EXPOSE 8080

RUN ["./gradlew", "clean", "build"]

CMD ["java", "-jar", "build/libs/spring-hello-world-0.0.1-SNAPSHOT.jar"]
