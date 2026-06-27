# Рамиль Сабирзянов (11.08.2011) 🚀

**Backend-разработчик (начинающий)**

---

## 🛠️ Стек

![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-teal?logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-blue?logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-7-red?logo=redis)
![Docker](https://img.shields.io/badge/Docker-28-blue?logo=docker)
![Nginx](https://img.shields.io/badge/Nginx-1.27-green?logo=nginx)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0-red)
![Alembic](https://img.shields.io/badge/Alembic-1.14-orange)
![Pytest](https://img.shields.io/badge/Pytest-7.4-blue?logo=pytest)
![JWT](https://img.shields.io/badge/JWT-RS256-blue)
![Ruff](https://img.shields.io/badge/code%20style-ruff-purple)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Argon2](https://img.shields.io/badge/Argon2-hashing-purple)
![uv](https://img.shields.io/badge/uv-0.6-blue)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF)
![Deploy](https://img.shields.io/badge/Deploy-Render-46C3C4)
![Rate Limiting](https://img.shields.io/badge/Rate%20Limiting-SlowAPI-purple)
![TTL](https://img.shields.io/badge/TTL-Supported-blue)
![MIT](https://img.shields.io/badge/License-MIT-yellow)
![QR Code](https://img.shields.io/badge/QR%20Code-Generated-brightgreen)

## 🚀 Лучшие проекты

### 🔹 Short URL (Новый флагман)

Сервис для сокращения ссылок с JWT-аутентификацией на асимметричных ключах, кэшированием и генерацией QR-кодов.

- Чистая архитектура (Service → Repository)
- JWT access (15 минут) + refresh (7 дней) с **RSA подписью**
- Изолированное кэширование в Redis (db=0 для кэша и `QR-кодов`, db=1 для `SlowAPI`)
- Генерация QR-кодов на лету без хранения бинарников в БД
- Система TTL для автоматического управления временем жизни ссылок
- Фоновые задачи через `FastAPI BackgroundTasks`
- Полный цикл тестирования (65+ зеленых тестов на `Pytest`)

🔗 [Репозиторий](https://github.com/hotpotato89/short-url) | [Swagger UI](https://short-url-8bjl.onrender.com/docs) | [Фронтенд](https://short-url-ui-9240.onrender.com)


### 🔹 FastAPI Playground

Production-ready REST API с JWT аутентификацией, refresh токенами, Docker и Nginx.

- FastAPI, PostgreSQL, SQLAlchemy, Alembic
- JWT access + refresh с RSA подписью
- Argon2 хэширование паролей
- Nginx reverse proxy + раздача статики
- Docker Compose (многоконтейнерная сборка)
- Чистая архитектура (Service → Repository)
- Логирование медленных запросов
- Глобальные exception handlers

🔗 [Репозиторий](https://github.com/hotpotato89/fastapi-playground)

---

### 🔹 User Center JWT

REST API с JWT авторизацией, кэшем и пагинацией. С фронтедном, сгенерированным с ИИ.

- FastAPI, PostgreSQL, Redis, Docker
- Сортировка, пагинация, кэширование через Redis
- Собственный декоратор @cache
- Юнит-тесты, Ruff
- Докер (multi-stage)
- Деплой на Render + Netlify

🔗 [Swagger](https://user-a0r5.onrender.com/docs) | [Фронт (*VPN-require*)](https://user-center-jwt.netlify.app)

---

Остальные проекты в репозиториях GitHub.
