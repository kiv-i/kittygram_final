# Kittygram

### О проекте

Kittygram — сервис для публикации данных о котиках. В нем можно добавить 
котиков, прикрепить изображение (не более 20МБ), выбрать цвет, выбрать 
или добавить достижения.

Это проект, который состоит из бэкенд-приложения на Django 
и фронтенд-приложения на React.

### Использованные технологии

* [Python](https://www.python.org/)
* [React](https://react.dev/)
* [Django](https://www.djangoproject.com/)
* [Django REST framework](https://www.django-rest-framework.org/)
* [Djoser](https://djoser.readthedocs.io/en/latest/getting_started.html)

### Примеры использования

Приложение доступно по адресу: https://kotygram.ddns.net/  
Где можно зарегистрироваться.  
Также доступно API: https://kotygram.ddns.net/api/  
Регистрация пользователя происходит при помощи библиотеки Djoser: 

```
POST: https://kotygram.ddns.net/api/users/
```

После этого необходимо получить токен:

```
POST: https://kotygram.ddns.net/api/token/login/
```

Дополнительные эндпоинты в документации [Djoser](https://djoser.readthedocs.io/en/latest/base_endpoints.html)  

Доступ через auth-token.  

Получить список котиков:

```
GET: https://kotygram.ddns.net/api/cats/
```

Получить список достижений:

```
GET: https://kotygram.ddns.net/api/achievements/
```
Так же доступны POST, PUT, PATCH, DELETE запросы.

### Авторы

* [Константин Иванов](https://github.com/kiv-i)