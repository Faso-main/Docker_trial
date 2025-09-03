# Используем официальный Python образ
FROM python:3.11-slim

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем файлы в контейнер
COPY app.py .

# Запускаем приложение
CMD ["python", "app.py"]