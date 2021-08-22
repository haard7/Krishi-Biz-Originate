# Tests(OPTIONAL but ho to accha!)

***OPTIONAL***

provide scripts or steps to test in this directory, same like in the main README's usage section.

How to use Our Webapp -:
*you must have downloaded python in your system*

1)open a folder on your desktop and give any name you want
2)open that folder in vs code.
3)open terminal in vs code and type "pip install django"
4)then in same terminal type "pip install psycopg2" and "pip install pillow"
5)Then in terminal type  "django-admin startproject mysite" in terminal this will automatically create a default project folder of django having manage.py file
6)Then create a new app by typing "python manage.py startapp your_appname" in terminal this will create a app / folder inside mysite folder
7)Now if you want to use default database(dbsqlite3) which is provided by django there is no need to make changes in setting.py
8)if you want to use postgresql you need to download postgresql from google and then make a table database named 'hackathon'(in my case or folder i had uploaded on github) or you can give and name to database and need to integrate it in settings.py file
9)Now run "python manage.py makemigrations" in terminal
10) run "python manage.py migrate" in terminal
11) Then run "python manage.py runserver" in terminal to run server and go to chrome and type 127...and your app will run
