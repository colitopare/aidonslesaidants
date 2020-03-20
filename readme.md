### Start

docker run --rm -v $(PWD):/app composer install
docker-compose -f .docker/docker-compose.yml up -d
