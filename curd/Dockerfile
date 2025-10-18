FROM maven:3.9.6-eclipse-temurin-21
WORKDIR /app
COPY . /app
RUN mvn clean install -DskipTests
CMD ["java", "-jar", "target/curd-0.0.1-SNAPSHOT.jar"]