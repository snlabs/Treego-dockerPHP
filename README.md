Image docker sbzteam/PHP
https://hub.docker.com/r/sbzteam/php

publier sur le Docker Hub

docker build -t sbzteam/php:7.4 .

docker login

docker tag sbzteam/php:7.4 sbzteam/php:7.4

docker push sbzteam/php:7.4

docker pull sbzteam/php:7.4
