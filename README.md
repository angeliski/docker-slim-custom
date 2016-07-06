# docker-slim-custom


Custom build for docker-slim.
run:

docker run -v ~/workspace/php/slim/:/var/www/html/api -d -p 8001:80 angeliski/docker-slim-custom

Is necessary put the .htaccess in the root app folder.