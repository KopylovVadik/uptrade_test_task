* `source run.sh install` - создаст виртуальное окружение, установит зависимости, применит миграции
* `sh run.sh run` - start server (или `python manage.py runserver`)


Для запуска приложения в докер-контейнере:
* `docker build`
* `docker run -p 8000:8000 (container_id)`
* из контейнера приложение доступно по адресу `127.0.0.1:8000`


** **
разработка и тестирование проводились на `mac_os(12.3.1)`.
