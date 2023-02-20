# blog-django

создание нашего django\n

django-admin startproject myblog

Запуск сервера
python manage.py runserver


Создание нового приложения
python manage.py startapp blog
После должны его зарегистрировать в settings.py INSTALLED_APPS = [


#проверка миграции 
python manage.py makemigrations 


Создание миграции
python manage.py migrate 


Создание Суперпользователя
python manage.py createsuperuser
