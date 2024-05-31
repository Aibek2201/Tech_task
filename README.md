Инструкция запуска проекта

Активация окружения:

    ```bash
    python3 -m venv venv
    venv/Scripts/activate
    ```

Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

Применить миграции:
    ```bash
    alembic upgrade head
    ```

Запуск проекта:
    ```bash
    python run.py

    http://127.0.0.1:8000/docs
    ```
