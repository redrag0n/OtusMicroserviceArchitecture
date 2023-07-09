# syntax=docker/dockerfile:1.4
FROM python:3

WORKDIR /src
COPY requirements.txt /src

RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 5000

CMD ["python3", "app.py"]