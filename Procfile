web: gunicorn project.server.__init__:app
heroku ps:scale web=1
release: python __init__.py db upgrade

