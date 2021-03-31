# Django transactional

A simple Django app for testing transactional email sending. Django template comes pre-configured for Sass. 

### To generate sass files 

Using [django-sass](https://github.com/coderedcorp/django-sass)

The following will watch for new updates in your sass files, but must be run alongside the server

`./manage.py sass static/sass/ static/css/ --watch`

Run the server and watch for new sass file changes:

`./manage.py sass static/sass/ static/css/ --watch & ./manage.py runserver`

### Generate a new secret key

`python generate_secret.py`
