web: gunicorn clinic.wsgi 
release: python manage.py makemigrations --noinput
release: python manage.py migrate --noinput
release: python manage.py runserver

