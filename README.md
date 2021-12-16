# Python
Create a virtual environment with `venv`
```
python3 -m venv <MYVENV>  
```

# Django
Create a project
```
django-admin startproject mysite
```
Create an app
```
python manage.py startapp myapp
```
Run server
```
python manage.py runserver
```
Run tests
```
python manage.py test
```
Make empty migration with chosen name
```
python manage.py makemigrations --empty APP --name NAME
```
# Celery
Run worker
```
celery -A project_name worker -l info
```
Run celery beat (periodic tasks)
```
celery -A project_name beat
```

# Vue
Create project (add . at the end to create in current dir)
```
vue create hello-world
```

Run project
```
npm run serve
```

# React
Create project
```
npx create-react-app my-app
```

Run project
```
npm start
```

Deploy to Github Pages
```
npm run deploy
```
[More about GH Pages](https://github.com/gitname/react-gh-pages)

# Heroku
Login
```
heroku login
```

Reset database
```
heroku pg:reset DATABASE
```

Run Django migrations
```
heroku run python manage.py migrate
```

# PostgreSQL

List databases
```
\l
```

Connect to database
```
\c NAME
```

List tables
```
\dt
```

# Linux

Set env var permamently
```
sudo vim /etc/environment
VAR="SOMETHING"
```

Set alias in ~/.bashrc
```
alias python='python3'
alias pip='pip3'
```

# Git
Set username and password
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
