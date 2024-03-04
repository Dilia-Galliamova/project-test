# Веб-сайт на Django 
Доска объявлений для фанатского сервера MMORPG

Доступны следующие функции:
- регистрация пользователя
- создание и редактирование объявлений с текстовым и мультимедийным контентом
- просмотр, удаление и прием откликов в личном кабинете
- получение email-уведомлений о действиях
- новостные рассылки для пользователей

## Запуск проекта
Для запуска в среде PyCharm необходимо:
- активировать виртуальную машину `venv\scripts\activate`
- перейти в в папку проекта `cd announcement`
- запустить сервер `python manage.py runserver`

Следующие конфиденциальные параметры в gitignore:
```
SECRET_KEY
EMAIL_HOST
EMAIL_PORT
EMAIL_HOST_USER 
EMAIL_HOST_PASSWORD
DEFAULT_FROM_EMAIL
CELERY_BROKER_URL
CELERY_RESULT_BACKEND

```
