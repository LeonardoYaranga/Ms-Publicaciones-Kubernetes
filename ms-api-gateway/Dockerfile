FROM eclipse-temurin:21-jdk-jammy
WORKDIR /app
COPY target/*.jar app.jar
EXPOSE 8000
ENV JAVA_OPTS="-Xmx512m -Xms256m"
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar app.jar"]