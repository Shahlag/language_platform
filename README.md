# language_platform

//SetUP

python -m venv myenv

myenv\Scripts\activate

pip install django

pip install --upgrade pip

python -m django --version


//Start Making Project start with creation

django-admin startproject language_platform

cd language_platform

python manage.py startapp learning

python manage.py migrate

python manage.py createsuperuser //for admin login 

//run the development server

python manage.py runserver

http://127.0.0.1:8000/
