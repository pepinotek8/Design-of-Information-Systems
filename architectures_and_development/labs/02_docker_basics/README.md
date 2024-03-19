# Useful commands

```bash
docker network
docker network ls
docker network create <network>
docker network inspect <network>
docker network connect <network> <image>
docker network disconnect <network> <image>
docker network rm <network>
docker run --network <network> -d <image>

docker volume ls
docker volume create <volume>
docker volume inspect <volume>
docker volume rm <volume>
docker run -v <volume> -d <image>


docker compose up --build -d 
docker compose down
```
