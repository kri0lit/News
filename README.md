# Новостной портал 
Сайт, где каждый может выставить свою новость или почитать чужие

## Описание 
Новостной сайт созданный с использованием микрофреймворка Flask.

## Технологии 
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить 
 1. Склонируйте репозиторий
 2. Создайте и активируйте виртуальное окружение
```comandline
python -m venv venv
source venv/Scripts/activate
```
3. Установите зависимости
```comandline
pip install -r requirements.txt
```
4. Создайте файл .env и укажите настройки подключения к БД и другие параметры.
```comandline
DATABASE_URI=sqlite:///db.sqlite3
SECRET_KEY=YOUR_SECRET_KEY
```
5. Запустите flask приложение
``` comandline
flask run
```
