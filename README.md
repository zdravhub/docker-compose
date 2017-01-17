# Wildfly, Postgres and Elasticsearch environment

### This repo cloning
```
git clone https://github.com/zdravhub/docker-compose.git
```
### Prerequisites
Install Docker Engine: https://docs.docker.com/engine/installation/

Install Docker Compose: https://docs.docker.com/compose/install/

### Containers initialization
```
docker-compose -f wildfly-postgres-elastic.yml up
```
### Health check
```
docker-compose -f wildfly-postgres-elastic.yml ps
```
### Bash login in containers
```
docker exec -it wildfly /bin/bash
docker exec -it postgres /bin/bash
docker exec -it elastic /bin/bash
```
