web: gunicorn crud.wsgi
release: python3 manage.py makemigrations --noinput
release: python3 mamange.py collectstatic --noinput
release: python manage.py migrate --noinput