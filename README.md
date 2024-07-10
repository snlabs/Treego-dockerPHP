Image docker sbzteam/PHP
https://hub.docker.com/r/sbzteam/php

publier sur le Docker Hub


docker build -t sbzteam/php:8.3-alpine .

docker login

docker tag sbzteam/php:8.3-alpine sbzteam/php:8.3-alpine

docker push sbzteam/php:8.3-alpine


docker pull sbzteam/php:8.3-alpine
