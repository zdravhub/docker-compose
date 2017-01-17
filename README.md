# Wildfly, Postgres and Elasticsearch environment

<b>This repo cloning</b>

git clone https://github.com/zdravhub/docker-compose.git

<hr>

<b>Containers initialization</b>

docker-compose -f wildfly-postgres-elastic.yml up

<hr>

<b>Health check</b>

docker-compose -f wildfly-postgres-elastic.yml ps

<hr>

<b>Bash login in containers</b>

docker exec -it wildfly /bin/bash

docker exec -it postgres /bin/bash

docker exec -it elastic /bin/bash
