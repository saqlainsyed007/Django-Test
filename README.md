# Django-Test


## Chrome Driver Installation steps(Mac)


Download Chrome Driver(Version 2.39): https://chromedriver.storage.googleapis.com/index.html


Unzip the downloaded file to get chromedriver executable


Copy the executable to '/usr/local/bin/': `cp <path to chromedriver executable> /usr/local/bin/`


## Project Setup


All commands executed from `<path to Django-Test>/todo` directory


### Create Virtual Environment
`mkvirtualenv django-test`


Activate virtual environment by executing command: `workon django-test`


### In the active `django-test` virtual environment, execute the following steps


Install requirements: `pip install -r requirements.txt`


Migrate: `python manage.py migrate`


Create Super User: `python manage.py createsuperuser`


Test: `python manage.py test`
