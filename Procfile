web: gunicorn --bind :8000 --workers 3 --threads 2 theislamicnation.asgi:application
chatworker: python manage.py runworker --settings=theislamicnation.settings -v2