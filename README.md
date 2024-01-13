Image docker sbzteam/PHP
https://hub.docker.com/r/sbzteam/php

publier sur le Docker Hub

docker build -t sbzteam/php:8.2-alpine .

docker login

docker tag sbzteam/php:8.2-alpine sbzteam/php:8.2-alpine


docker pull sbzteam/php:tagname (tagname = 8.2-alpine)
