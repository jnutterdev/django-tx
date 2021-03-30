# Starter Django project 3.1.7

This is a simple starter project that I created that is setup with one template view, sass, and some partial barebones. 

It is not setup with a database or models, so that would need to be setup afterward.

### To generate sass files 

Using [django-sass](https://github.com/coderedcorp/django-sass)

- For the main stylesheet:
`python manage.py sass project/scss/style.scss static/css/style.css -g`

- Watch for updates in development:
`python manage.py sass project/scss/ static/css/ --watch`

### Generate a new secret key

`python generate_secret.py`