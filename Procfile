web: gunicorn project.server.__init__:app
heroku ps:scale web=1
release: bash launch.sh db upgrade
