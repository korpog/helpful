# Django
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
python manage.py makemigrations --empty --name NAME
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
