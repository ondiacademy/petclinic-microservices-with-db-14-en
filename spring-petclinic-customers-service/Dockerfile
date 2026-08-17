FROM eclipse-temurin:11-jre
COPY ./target/*.jar /app.jar
ENV SPRING_PROFILES_ACTIVE docker,mysql
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "/app.jar"]