# ДЗ номер 2

## Докер-образ
cd app

docker build . --tag joinmek/healthcheck-service

docker run -p 8000:8000 healthcheck-service

## Docker hub
https://hub.docker.com/r/joinmek/healthcheck-service
