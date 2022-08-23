## Initialization

install django ```pip install django```

start a project ```django-admin startproject todo_list```

create a base app ```python manage.py startapp base```

## connectio port
http://127.0.0.1:8000/

## urls, views and models

code in urls.py, views.py and models.py

**file migration**: 
- ```python manage.py makemigrations```
- Then run migration ```python manage.py migrate```


- About Django app model makemigrations: makemigrations basically generates the SQL commands for preinstalled apps (which can be viewed in installed apps in settings.py) and your newly created apps’ model which you add in installed apps. It does not execute those commands in your database file. 

## Create user
```python manage.py createsuperuser```
- Username (leave blank to use 'wang1'): cici
- Email address: cici@email.com
- Password: cici

## Function of create/edit/delete task

## Function of log in/log out/task shows and save specific to each user/register
- Django handle user authentification using Session