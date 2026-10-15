# syntax=docker/dockerfile:1
FROM python:3.15-alpine
ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
