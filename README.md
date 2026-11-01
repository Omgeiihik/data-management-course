Учебный репозиторий курса. Группа ВМО-41/42.
 
## Структура
- `docker-compose.yml` — PostgreSQL + pgAdmin
- `requirements.txt` — зависимости Python
- `sql/` — DDL-скрипты и запросы по неделям
- `scripts/` — Python-скрипты (ETL, генерация данных, проверки)
- `docs/` — отчёты и документы по лабораторным работам
 
## Как запустить окружение
1. `docker compose up -d`
2. `py -3.12 -m venv venv`
    `.\venv\Scripts\Activate.ps1`
3. `pip install -r requirements.txt`
4. `python scripts/test_connection.py`
 
## Автор
Кисель Евгений, ВМО-42
