FROM openjdk:21-jdk-slim AS build
WORKDIR /app
COPY..
RUN./gradlew build -x test

FROM openjdk:21-jdk-slim AS runtime
WORKDIR /app
COPY --from=build /app/build/libs/project.jar project.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "project.jar"]