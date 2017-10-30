# Setup on MS Windows

This document is designed for MS Windows users.

## Install Python3 
Download the latest version of Python from [https://www.python.org/downloads/](https://www.python.org/downloads/)


## Install virtualenv 
notice that Python includes pip with it from the version of 3.4

```
$ python -m pip install virtualenv

```



## Create a Django Project
```
$ mkdir django-tutorial
$ cd django-tutorial

$ py -m virtualenv env
```
### Activate & Deactivate virtual environment
```
$ .env\Scripts\activate

$ .env\Scripts\deactivate
```

once you activate your virtual environment, you can run django-amdin

```
$ pip install django
$ django-admin startproject mysite

$ cd mysite
$ python manage.py runserver
```

You can see following logs
Starting development server at http://127.0.0.1:8000
Quit the server with CTRL-BREAK.


## Resources
[https://docs.djangoproject.com/en/1.11/intro/tutorial01/](https://docs.djangoproject.com/en/1.11/intro/tutorial01/)