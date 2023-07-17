- install django gunicorn - pip3 install django<4 gunicorn
- add installed apps to requirements.txt - pip3 freeze --local > requirements.txt
- create project - django-admin startproject website .
- create app - python3 manage.py startapp main
- add app to settings.py 'installed apps'
- migrate migrations - python3 manage.py migrate
- in env - os.environ["SECRET_KEY"DATABASE_URL"]='keys
ins settings - os.environ["SECRET_KEY"]'default': dj_database_url.parse(os.environ.get("DATABASE_URL"))