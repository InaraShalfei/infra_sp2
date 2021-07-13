# Проект "Yamdb"
### Описание
Проект YaMDb собирает отзывы (Review) пользователей на произведения (Titles).
### Команда для запуска приложения
```
docker-compose up -d --build 
```
### Команда для создания суперпользователя
```
docker-compose exec web python manage.py createsuperuser
```
### Команда для заполнения базы начальными данными
```
docker-compose exec web python manage.py loaddata fixtures.json
```
