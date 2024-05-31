Инструкция запуска проекта

Активация окружения:

    python3 -m venv venv
    venv/Scripts/activate


Установите зависимости:
    pip install -r requirements.txt


Применить миграции:

    alembic upgrade head


Запуск проекта:
    python run.py

    http://127.0.0.1:8000/docs

