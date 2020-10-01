# Django Crash Course
###### https://www.youtube.com/watch?v=xv_bwpA_aEA&list=PL-51WBLyFTg2vW-_6XBoUpE7vpmoR3ztO&ab_channel=DennisIvy

## Install Django
```
pip3 install django
```

## Create Project
```
django-admin startproject [PROJECT NAME]
```

## Run Project
```
python3 manage.py runserver
```

## Create App in Project
```
python3 manage.py startapp [APP NAME]
```

## Add App in Settings.py
```
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    
    ['APP NAME'],
]
```