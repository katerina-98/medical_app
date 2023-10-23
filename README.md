установка зависимостей и запуск сервера
1. ```pip install -r requirements.txt``` - установка внешних приложений, необходимых для запуска
2. ```python manage.py migrate``` - перенос схемы базы данных из миграций в базу данных
3. ```python manage.py runserver``` - запуск сервера (веб-приложения)


сохранение зависимостей
```pip freeze > requirements.txt```
