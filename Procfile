web: gunicorn backend.wsgi --timeout 120 --workers 1

release: python manage.py makemigrations && python manage.py migrate
