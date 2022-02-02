web: gunicorn project.server.__init__:app
heroku ps:scale web=1
release: 
flask db init
flask db migrate
flask db upgrade
#flask run --host=0.0.0.0 --port=5000
flask run