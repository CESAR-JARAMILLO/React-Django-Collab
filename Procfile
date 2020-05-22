web: gunicorn leadmanager.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
leadmanager/manage.py migrate
