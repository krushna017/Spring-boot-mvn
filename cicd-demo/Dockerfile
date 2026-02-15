FROM eclipse-temurin:21-jdk-jammy

WORKDIR /app

COPY cicd-demo-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8888

ENTRYPOINT ["java","-jar","app.jar"]
