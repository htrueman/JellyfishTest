# Jellyfish Test Chat

# How to run server:
$ wget http://download.redis.io/redis-stable.tar.gz

$ tar xvzf redis-stable.tar.gz

$ cd redis-stable

$ make

$ sudo make install

$ redis-server

$ git clone git@github.com:htrueman/JellyfishTest.git

$ cd JellyfishTest/jellyfish

$ sudo -u postgres psql

	CREATE DATABASE jellyfish_heroku;

$ virtualenv .venv --no-site-packages

$ source .venv/bin/activate

$ pip install -r requirements.txt

$ python manage.py migrate

$ python manage.py runserver
