# Notes API (nodejs-hw)

Простий Express.js сервер для колекції нотаток.

## Технології

- Node.js
- Express.js
- cors
- dotenv
- pino-http

## Встановлення

Виконати команду: npm install

## Запуск

Створи файл .env зі змінною:

PORT=3000

Запусти сервер командою: npm start
або: node src/server.js

## Маршрути

| Метод | Маршрут        | Опис                      |
| ----- | -------------- | ------------------------- |
| GET   | /notes         | Отримати всі нотатки      |
| GET   | /notes/:noteId | Отримати нотатку за ID    |
| GET   | /test-error    | Перевірка обробки помилок |
