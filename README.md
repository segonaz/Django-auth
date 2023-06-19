# Django-auth
Django's authentication system app

Приложение реализует возможности Django's authentication system:
* Используется измененная стандартная модель пользователя, для логина по email вместо username
* Регистрация пользователя, отправка проверочного сообщения на email (письма выводятся в консоль)
* Аутентификация
* Сброс пароля через email
* Пример работы с профайлом
* Шаблоны изменены для работы c Bootstrap

### Установка и запуск:
- cd where-you-keep-your-projects

```shell
git clone git@github.com:segonaz/Django-auth.git
```
```shell
cd Django-auth && poetry install --only main
```
```shell 
source  .venv/bin/activate
```
```shell 
cd django-auth && python3 manage.py migrate
```
```shell 
python manage.py runserver
```
