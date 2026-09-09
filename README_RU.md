# Даниил Романович

**AI & Automation Engineer / Специалист по автоматизации бизнес-процессов**

Разрабатываю AI-системы, backend-интеграции и многоэтапные автоматизации: от анализа процесса и проектирования архитектуры до реализации, тестирования и передачи решения.

## Стек

**AI:** OpenAI API · RAG · LangGraph · MCP · embeddings · vector search  
**Backend:** Python · FastAPI · PostgreSQL · Redis · Celery · SQLAlchemy · REST API · Webhooks  
**Automation:** n8n · JavaScript · JSON · Telegram Bot API  
**Engineering:** Docker · Git · GitHub Actions · тестирование · техническая документация

## Что теперь подтверждается кодом и CI

- **RAG Knowledge Assistant:** FastAPI → PostgreSQL/pgvector → retrieval → grounded response + Redis cache; integration test работает с реальными PostgreSQL/pgvector и Redis в GitHub Actions.
- **Multi-Agent Business Assistant:** LangGraph routing, сохранение run state и human approval flow проверяются через FastAPI integration test.
- **AI Integration Service:** GitHub Actions поднимает полный Docker Compose stack и прогоняет задачу по цепочке API → Redis/Celery → worker → demo upstream → PostgreSQL.

Публичные Python-проекты оформлены как portfolio/reference implementations, а не как заявление о customer production deployment. Уровень проверки описан в README каждого проекта.

Английская версия `README.md` предназначена для главной страницы GitHub-профиля.
