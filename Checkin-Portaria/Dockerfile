FROM openjdk:7
WORKDIR /app
COPY app.jar /app/app.jar
COPY config.ini /app/config.ini
EXPOSE 3001
CMD ["java", "-jar", "app.jar"]