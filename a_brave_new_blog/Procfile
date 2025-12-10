web: gunicorn --config gunicorn.conf.py a_brave_new_blog.wsgi

# Uncomment this `release` process if you are using a database, so that Django's model

release: ./manage.py migrate --no-input
