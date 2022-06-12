FROM python:3.8-slim

RUN mkdir /app
ADD . /app
WORKDIR /app

EXPOSE 8000

RUN pip install -r /app/requirements.txt

CMD ["python",  "manage.py",  "runserver",  "0.0.0.0:8000"]