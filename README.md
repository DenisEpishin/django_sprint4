# Django Sprint 4
# Приложение «Блогикум».

## Описание
«Блогикум» - это учебный проект на Django, созданный для демонстрации различных аспектов разработки веб-приложений.
Пользователи могут создавать свои страницы и публиковать на них сообщения ("посты").

## Установка
Для установки и запуска проекта выполните следующие шаги:

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/DenisEpishin/django_sprint4
    ```
2. Перейдите в директорию проекта:
    ```bash
    cd django_sprint4
    ```
3. Создайте виртуальное окружение:
    ```bash
    python -m venv venv
    ```
4. Активируйте виртуальное окружение:
    - Для Windows:
        ```bash
        venv\Scripts\activate
        ```
    - Для macOS и Linux:
        ```bash
        source venv/bin/activate
        ```
5. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```
6. Перейдите в директорию приложения:
    ```bash
    cd blogicum
    ```
6. Проведите миграции:
    ```bash
    python manage.py migrate
    ```
7. Опционально, загрузите тестовые данные:
    ```bash
    python manage.py loaddata db.json
    ```
8. Опционально, создайте суперпользователя:
    ```bash
    python manage.py createsuperuser
    ```

## Запуск
Для запуска сервера разработки выполните команду:
```bash
python manage.py runserver
```

Тестирование
Проект содержит набор тестов, которые можно запустить с помощью pytest. Для этого из папки django_sprint4 выполните:
```bash
pytest
```
