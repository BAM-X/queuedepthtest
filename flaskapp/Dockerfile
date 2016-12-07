FROM python:2.7

WORKDIR /app

ADD requirements.txt /app/
RUN pip install -r requirements.txt

ADD flaskapp.py uwsgi.conf /app/
