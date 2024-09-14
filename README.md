Procfile

web: gunicorn webdev:app


pip freeze > "requirements.txt"
