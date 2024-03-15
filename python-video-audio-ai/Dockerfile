FROM python:3.8-slim-buster

RUN apt-get update && apt-get install ffmpeg libsm6 libxext6  -y
RUN pip install --upgrade pip

WORKDIR /app
COPY requirements.txt /app

RUN pip3 install -r requirements.txt
