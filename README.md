# ДЗ номер 3

## Докер-образ
docker build . --tag joinmek/healthcheck-service

docker run -p 8000:8000 healthcheck-service

## Docker hub
https://hub.docker.com/r/joinmek/healthcheck-service

## Запуск
kubectl apply -f k8s/