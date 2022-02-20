Pre-requisites:
    Python(version > 3.6)
    Pip(latest)

Create & activate a virtual environment:
    1. pip install virtualenv
    2. virtualenv env_name
    3. env_name\Scripts\activate

Install all dependencies:
    1. pip install -r requirements.txt

Database setup:
    1. Change database configuration settings.py
    2. Run "Python manage.py makemigrations"
    3. Run "Python manage.py migrate"

Create a superuser:
   1. Run "Python manage.py createsuperuser"
      
Run django server on a localhost:
    1. Run "Python manage.py runserver"