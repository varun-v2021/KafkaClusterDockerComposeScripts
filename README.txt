powershell in admin mode on windows


docker-compose -f .\kafka-cluster.yml up

docker-compose -f .\kafka-cluster.yml down

docker-compose -f producer-consumer.yml up --scale consumer=3

docker-compose -f producer-consumer.yml down