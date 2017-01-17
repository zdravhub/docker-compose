# Wildfly, Postgres and Elasticsearch environment

<b>Containers initialization</b>

docker-compose -f wildfly-postgres-elastic.yml up

<hr>

<b>Health check</b>

docker-compose ps

<hr>

<b>Bash login in containers</b>

docker exec -it wildfly /bin/bash

docker exec -it postgres /bin/bash

docker exec -it elastic /bin/bash
