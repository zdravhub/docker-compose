# Wildfly, Postgres and Elasticsearch environment

<b>This repo cloning</b>

<pre>git clone https://github.com/zdravhub/docker-compose.git</pre>

<hr>

<b>Containers initialization</b>

<pre>docker-compose -f wildfly-postgres-elastic.yml up</pre>

<hr>

<b>Health check</b>

<pre>docker-compose -f wildfly-postgres-elastic.yml ps</pre>

<hr>

<b>Bash login in containers</b>
<pre>
docker exec -it wildfly /bin/bash

docker exec -it postgres /bin/bash

docker exec -it elastic /bin/bash
</pre>
