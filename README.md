# Starter Django project 3.1.7

This is a simple starter project that I created that is setup with one template view, sass, and some partial barebones. 

It is not setup with a database or models, so that would need to be setup afterward.

### To generate sass files 

Using [django-sass](https://github.com/coderedcorp/django-sass)

The following will watch for new updates in your sass files, but must be run alongside the server

`./manage.py sass static/sass/ static/css/ --watch`

Run the server and watch for new sass file changes:

`./manage.py sass static/sass/ static/css/ --watch & ./manage.py runserver`

### Generate a new secret key

`python generate_secret.py`
