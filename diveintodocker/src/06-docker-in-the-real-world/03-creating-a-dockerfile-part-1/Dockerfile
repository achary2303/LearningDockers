FROM python:3.6-alpine

RUN mkdir /app
WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . . 


LABEL	maintainer="Arun Chary! <arunchary323@gmail.com>"\
		version="1.0"


CMD flask run --host=0.0.0.0 --port=5000
