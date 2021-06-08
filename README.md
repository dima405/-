# Quick Start
## Windows
### Создание виртуального окружения
```
pip install virtualenv
virtualenv venv
venv\Scripts\activate
```
### Установка зависимостей
```
pip install -r requirements.txt
```
### Добавление переменной окружения и режим отладки
```
set FLASK_APP=flasky.py
set FLASK_DEBUG=1
```
### Регистрация SMTP и почта администратора
```
set MAIL_USERNAME=почта
set MAIL_PASSWORD=пароль
set FLASKY_ADMIN=почта
```
### Работа с базой данных
```
flask db init
flask db migrate
flask db upgrade
```
### Тестирование и запуск приложения
```
flask test
flask run
```
