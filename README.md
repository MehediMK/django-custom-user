<h1 align='center'>Django-custom-user</h1>


## Prerequisites
  - Python 3.8+
  - Virtualenv and Pip

## How to Run this Project

  - First of all clone this Project
  - `cd <project_directory>` 
  - create a virtual env `python -m venv venv`
  - For activate env write on you terminal `source venv/bin/activate` (*linux) on `venv\Scripts\activate` (Windows)
  - Install packages `pip install -r requirements.txt`
  - For configure `copy "config.py sample" config.py`
  - Run on your terminal `python manage.py migrate`
  - Run `python manage.py runserver`

## Helpful commands
  - `python manage.py makemigrations` "for migration"
  - `python manage.py makemigrations <app_name>` "for migration"
  - `python manage.py runserver host:port` "for starting dev. server"
  - `python manage.py startapp app_name` "for new app"
  - `python manage.py createsuperuser` "For create superuser"

