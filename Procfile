release: python manage.py migrate
web: gunicorn todoro.wsgi --log-file -
web: python manage.py runserver 0.0.0.0:8000