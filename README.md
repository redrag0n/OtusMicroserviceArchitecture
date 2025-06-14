# ДЗ 1

cd app

docker build . --tag otus_l1

docker run -p 8000:8000 otus_l1
