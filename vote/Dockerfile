FROM python:3.6.4-slim

RUN pip install --upgrade pip

ENV PYTHONUNBUFFERED 1

RUN mkdir /app
WORKDIR /app

COPY . .

RUN pip3 install -r requirements.txt