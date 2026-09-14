### 05-virt-03-docker-intro
## Задача 1
# Dockerfile
```
FROM nginx:1.29.0
COPY ./index.html /usr/share/nginx/html/index.html
```
# URL on my nginx-custom image
https://hub.docker.com/r/darthdavos/custom-nginx
