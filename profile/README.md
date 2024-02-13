# Описание

В течение 6 месяцев разрабатывался учебный проект "Онлайн-кинотеатр"

# Созданные сервисы

- ETL для перегрузки данных из PostgreSQL в ElasticSearch (PostgreSQL, ElasticSearch, asyncpg2) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/postgres-elastic-etl)
- АПИ для доступа к контенту(фильмы, персоны, жанры) (FastAPI, PostgreSQL, SQLModel, Redis, Jaeger, ELK, pytest) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/content)
- Сервис отправки уведомлений для пользователя (FastAPI, Docker, Docker Compose, RabbitMQ, pytest) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/notification)
- Сервис для хранения и анализа пользовательских данных (ClickHouse, Kafka, FastAPI, pytest) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/ugc1)
- Сервис пользовательского контента (FastAPI, MongoDB, Beanie, pytest) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/ugc2)
- Сервис для аутентификации, авторизации (FastAPI, JWT, SQLModel, Jaeger, pytest) [Репозиторий](https://github.com/likeinlife-Yandex-Practicum/auth)

# Изученные технологии

1. Django, DRF, FastAPI
2. Docker, Docker Compose
3. ELK (ElasticSearch, Logstash, Kibana)
4. ElasticSearch (как отдельный сервис)
5. Jaeger
6. PostgreSQL, MongoDB, SQLite
7. Kafka
8. RabbitMQ
9. Redis (кэширование и хранение данных)
10. pytest
11. ClickHouse
12. JWT-токены
13. ORM: Django, SQLAlchemy, SQLModel(адаптация SQLAlchemy под Pydantic), Beanie (для MongoDB)
