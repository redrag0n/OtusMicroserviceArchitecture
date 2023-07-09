# ДЗ 1

cd app

docker build . --tag otus_l1

docker run -p 5000:5000 otus_l1
