# Hello World program in django
Hello, this is my first django program, a hello world program. 
To set up django, the following steps must be followed:

1)Install django:This can be done by a simple pip install but the best way to do it  would be in a virtual environment
$ pip install django

2)Set up a django project: This can be done by the following cammand:
$ django-admin startproject mysite
This will create a mysite directory containing many files

3)Creating the hello world app: This can be done by executing the following command from the mysite directory:
$ python3 manage.py startapp hello_world

4)Now writing the code according to the needs.

5)Tesing the app using the following command:
$ python3 manage.py runserver
To view the page go to localhost:<port>
  
6)Creating a superuser:In order to access the admin page we need a user.This can be done by the following command:
$ python3 manage.py createsuperuser
Username:
Email address:
Password:
Password (again):
Superuser created successfully.

7)Logging in to admin page by going to - localhost:<port>/admin .
