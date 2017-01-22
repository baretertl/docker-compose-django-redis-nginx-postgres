FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /app_code
WORKDIR /app_code
ADD requirements.txt /app_code/
RUN pip install -r requirements.txt
ADD . /app_code/