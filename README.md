# Привет, я Денис 👋
### Python Backend Developer

Разрабатываю надежные, асинхронные веб-сервисы и REST API на **Python (FastAPI)**.  
Уделяю внимание чистой слоистой архитектуре (Repository, Service, UoW), проектированию реляционных баз данных (**PostgreSQL / SQLAlchemy 2.0**) и контейнеризации (**Docker**).

- 🚀 **Опыт деплоя и поддержки production-сервисов:** настройка Nginx, Docker Compose, SSL, VPS.
- ⚡ **Современный стек:** FastAPI, SQLAlchemy 2.0 (AsyncIO), Pydantic v2, uv, Alembic.
- 🎯 **В фокусе:** масштабируемость, фоновые очереди (Redis / Celery), автотестирование (Pytest), CI/CD.
- 📍 **Формат работы:** Удалёнка / Релокация / Офис

---

### 🛠 Технологический стек

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Alembic-2B2B2B?style=for-the-badge&logo=alembic&logoColor=white" alt="Alembic" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white" alt="uv" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

### 🌟 Ключевые проекты

#### 🚗 [WRAP TOON — Веб-сервис студии автодетейлинга](https://github.com/dennchikus/wraptoon)
> 🌐 **Production Live Demo:** [wraptoon.ru](https://wraptoon.ru)  
* **Назначение:** Сервис для автоматизации клиентского пути студии стайлинга и оклейки авто (интерактивный калькулятор сметы в реальном времени, оформление заявок и консультаций, административный контур).
* **Архитектурные особенности:**
  - Асинхронный REST API на **FastAPI** с паттерном Repository и сессионным менеджером транзакций.
  - Реляционная БД **PostgreSQL 16** + **SQLAlchemy 2.0 (asyncpg)**, управление миграциями через **Alembic**.
  - Неблокирующие фоновые Telegram-уведомления через `BackgroundTasks` и асинхронный клиент `HTTPX` (с поддержкой прокси).
  - Защита административных и мутирующих эндпоинтов заголовком `X-Admin-Token` с защитой от атак по времени (`secrets.compare_digest`).
  - Разделение сред (DEV / PROD) с автоматическим отключением Swagger UI / OpenAPI в боевом режиме.
  - Полная контейнеризация (**Docker Compose**) и развёртывание на VPS с реверс-прокси **Nginx** и HTTPS/SSL.
* **Стек:** `Python 3.13`, `FastAPI`, `SQLAlchemy 2.0`, `PostgreSQL`, `Alembic`, `Docker Compose`, `Nginx`, `uv`.

---

#### 🏨 [Hotel Booking Service](https://github.com/dennchikus/backendCourse)
* **Назначение:** Сервис бронирования отелей и номеров с фильтрацией по датам и ценам, ролевой моделью пользователей и JWT-авторизацией.
* **Стек:** `Python`, `FastAPI`, `SQLAlchemy (Async)`, `PostgreSQL`, `Alembic`, `Docker`.

---

### 📊 Статистика активности

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dennchikus&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Denis's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dennchikus&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

### 📫 Контакты для связи

- 📧 **Email:** [mdiris@vk.com](mailto:mdiris@vk.com)
- 💬 **Telegram:** [@dennchikus](https://t.me/dennchikus) *(или укажи актуальный ник)*
- 🌐 **Портфолио в проде:** [wraptoon.ru](https://wraptoon.ru)
