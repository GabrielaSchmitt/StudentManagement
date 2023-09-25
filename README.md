# StudentManagement
Student Management System


## Bash Virtual Environment running commands:
1. python -m venv venv 
2. source venv/bin/activate

## Django  
1. pip install django
2. django-admin startproject django_project .

## Run the server
1. python manage.py runserver 
2. open the link on the given port

##
1. python manage.py startapp students
2. Add this project to your django_project/settings apps 

## after having a models run
1. python manage.py makemigrations

if the models were created sucessfully run the command
1. python manage.py migrate 

# for administrative tasks use admin.py 
1. python manage.py createsuperuser