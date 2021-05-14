FROM python:3.8

ADD . /www
WORKDIR /www

RUN python -m pip install --upgrade pip
RUN pip install -r requirements.txt

CMD uwsgi uwsgi.ini