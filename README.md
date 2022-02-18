# nambangkripto

[![Build Status](https://ci.imarukita.ninja/api/badges/rukita-team/rkt-backend/status.svg)](https://ci.imarukita.ninja/rukita-team/rkt-backend)

Requirement
------------
* python3
* virtualenv

Installation
------------
If you want clean python env on your system you can use pyenv which is explain [here](https://github.com/pyenv/pyenv)


```
$ pip install -U pipenv virtualenv pip
$ cp .env.example .env
$ virtualenv .venv
$ pipenv install --dev
```

* Learn basic [pipenv](https://docs.pipenv.org/en/latest/basics/)

* Learn basic [virutalenv](https://virtualenv.pypa.io/en/stable/userguide/)


Migration
---------
Everytimes you make change to models run command bellow.

please refer to [Documetation](https://docs.djangoproject.com/en/2.2/intro/overview/)
```
$ pipenv run ./manage.py makemigrations
$ pipenv run ./manage.py migrate
```

Up and Running
--------------
To run development inside virtualenv
``` 
$ pipenv run ./manage.py runserver
```

without using pipenv
```
$ pipenv shell
$ ./manage.py runserver
```

Testing
--------------
To run BDD testing
``` 
$ pipenv run ./manage.py behave
```
To see code coverage
``` 
$ pipenv run ./manage.py coverage run
```

prod version: 1.6.1

Support
-------
* abdu.muttaqiin@gmail.com
