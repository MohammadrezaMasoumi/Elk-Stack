# Docker-Compose

This docker-compose run 3 cluster node elasticsearch with kibana and logstash 

We should set vm.max_map_count to 262144 because Elasticsearch node controller will fail if this option doesnt set.
sysctl -w vm.max_map_count=262144 
sysctl -p


# Initiate Docker Compose
docker-compose up -d
