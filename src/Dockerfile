# Используем базовый образ с Java
FROM openjdk:17-jre-slim

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем JAR-файл из локальной директории в контейнер
COPY target/your-application.jar /app/your-application.jar

# Опционально, можно указать порт, на котором работает приложение
EXPOSE 8080

# Запускаем приложение при старте контейнера
CMD ["java", "-jar", "your-application.jar"]
