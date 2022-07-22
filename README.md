# DRF API for cinema service

## How to install:

PostgresSQL needed

```shell
git clone https://github.com/Flashmobber/cinema-django-rest-api.git
cd cinema-django-rest-api
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<db hostname>
set DB_NAME=<db name>
set DB_USER=<db username>
set DB_PASSWORD=<db password>
set SECRET_KEY=<secret key>
python manage.py createsuperuser
python manage.py runserver
```

## Dockerize project

Installed Docker needed

```shell
docker-compose build
docker-compose up
```

## Available functionality:

* Endpoints list /api/doc/swagger/
* Creating movies with genres and actors
* Adding images for movies
* Creating cinema halls
* Creating orders and tickets
* Adding movie sessions
* Filtering movies and movie sessions
* User permissions
* Django admin panel available