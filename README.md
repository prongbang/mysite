# Install library
```
pip3 install django
pip3 install djangorestframework
```

# Create a requirements.txt file 
```
touch requirements.txt
```
# And add the installed requirements into the text file
```
pip freeze > requirements.txt
```

# Creating a project
```
django-admin startproject mysite
```

# The development server
## Run
```
python3 manage.py runserver
```

## Run with post
```
$ python3 manage.py runserver 8080
```

## Run use server IP
```
python3 manage.py runserver 0:8000
```

# Creating the Polls app

> To create your app, make sure you’re in the same directory as manage.py and type this command:
```
python3 manage.py startapp polls
```

# Create super user
```
python3 manage.py createsuperuser
```
or
```
python manage.py createsuperuser --email admin@example.com --username admin
```
> User
```
u: prongbang
e: prongbang@gmail.com
p: xE4admin
```

# Create api
```
python3 manage.py startapp api
```

# Test
```
python3 manage.py test
```

# Migration
```
python3 manage.py makemigrations
```