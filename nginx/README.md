# Common Commands

```bash
docker build --build-arg TIMEZONE_CONFIG=America/Lima -t nginx:1.19.6-alpine -f nginx:1.19.6-alpine .
```
```bash
sudo docker run --name nginxtest1 -p 80:80 -d nginx:1.19.6-alpine

sudo docker exec -it nginxtest1 sh