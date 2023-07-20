release: python manage.py migrate --noinput
web: gunicorn -c gunicorn.conf pydotorg.wsgi
