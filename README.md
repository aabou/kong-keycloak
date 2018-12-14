# kong-keycloak

$ docker build -t kong:0.14-centos-oidc docker/kong/

$ docker-compose up -d kong-db

$ docker-compose run --rm kong kong migrations up

$ docker-compose up -d kong

$ docker-compose up -d keycloak-db

$ docker-compose ps

