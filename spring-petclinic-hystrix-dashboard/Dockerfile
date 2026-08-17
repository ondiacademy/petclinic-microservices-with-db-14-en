FROM eclipse-temurin:11-jre
COPY ./target/*.jar /app.jar
ENV SPRING_PROFILES_ACTIVE docker
EXPOSE 7979
ENTRYPOINT ["java", "-jar", "/app.jar"]