# dockerServices
dockerServices
docker stack deploy -c docker-compose.yml web0001 

docker service update --image mengmanzbh/productservice:latest web0001_product-service



docker service rollback web0001_product-service
