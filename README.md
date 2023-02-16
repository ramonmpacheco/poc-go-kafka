# poc-go-kafka
GoLang + Kafka

$ docker-compose ps

$ docker exec -it gokafka /bin/bash

$ go mod init {mod_name}

kafka-topics --create --bootstrap-server=localhost:9092 --topic=teste --partitions=3

kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste