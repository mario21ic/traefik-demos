## Up

docker-compose up -d

http://localhost:8080/api/rawdata

Whoami
curl -H Host:whoami.docker.localhost http://127.0.0.1

## Scale
docker-compose up -d --scale whoami=2
curl -H Host:whoami.docker.localhost http://127.0.0.1
curl -H Host:whoami.docker.localhost http://127.0.0.1

curl -H Host:nginx.docker.localhost http://127.0.0.1
