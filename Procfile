web: gunicorn mysite.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --no input
manage.py migrate