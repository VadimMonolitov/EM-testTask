# Effective Mobile Test Task

## Запуск проекта

```bash
# 1. Клонировать репозиторий
git clone https://github.com/VadimMonolitov/EM-testTask.git
cd EM-testTask

# 2. Запустить Docker Compose
docker-compose up --build

# 3. Проверка результата в браузере или:
curl http://localhost/
```

Как работает схема: 
1. Получаем трафик на Nginx порт 80
2. Трафик перенаправляется на Backend порт 8080
3. От Backend ответ "Hello from Effective Mobile!"
