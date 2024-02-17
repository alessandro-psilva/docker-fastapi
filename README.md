# docker-fastapi

## docker build
docker build -t docker-fastapi .

## docker run
docker run -d --name container-fastapi -p 80:80 docker-fastapi

## api endpoint
- Hello World! : http://127.0.0.1/
- Items/Id : http://127.0.0.1/items/5?q=somequery
