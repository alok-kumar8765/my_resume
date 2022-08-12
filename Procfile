# web: waitress-serve --port=$PORT resume_demo.wsgi:application 
# web: python manage.py runserver 0.0.0.0:$PORT
# release: python manage.py migrate
web: gunicorn resume_demo.wsgi --log-file -