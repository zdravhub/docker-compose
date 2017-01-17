# docker-compose
Docker-compose files

# Containers initialization
docker-compose -f wildfly-postgres-elastic.yml up

# Health check
docker-compose ps

# Bash login in containers
docker exec -it wildfly /bin/bash

docker exec -it postgres /bin/bash

docker exec -it elastic /bin/bash
