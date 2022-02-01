web: gunicorn launch:app
heroku ps:scale web=1
release: bash launch.sh db upgrade

