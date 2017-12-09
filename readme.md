# GikGak HTTP API
**Stability: 1 - Experimental**

## Description
GikGak backend server to store user data

## Stack
* Python 3.6.3
* Django 2.0

## Dev
I personally use [pyenv](https://github.com/pyenv/pyenv) to switch between Python version.

Follow [Django 2.0 installation guide](https://docs.djangoproject.com/en/2.0/intro/install/) if you haven't done it yet.

### VS Code
We use [Visual Studio Code](https://code.visualstudio.com/). Consider using it if you want do develop faster.
Here are the tasks we use:
* `Migrate db`
* Default Build : `Run server`

## Other IDE/Text editor
* Run `python manage.py migrate` to update DB scheme.
* Run `python manage.py runserver` to launch the server
