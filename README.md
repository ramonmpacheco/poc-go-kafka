# POC-GO-KAFKA
> GoLang + Kafka

<br/> 

> PARA VER OS NOMES DOS CONTAINERS:
> >
> ```$ docker-compose ps```

> PARA ACESSAR UM CONTAINER:
> 
> ```docker exec -it gokafka /bin/bash```

> PARA INICIAR UM MÓDULO:
> 
> ```$ go mod init {mod_name}```

> Obs: execute o ```go run cmd/producer/main.go``` dentro do container "gokafka" se não pode dar erro de serviço não encontrado.

> PARA CRIAR UM TÓPICO
> 
> ```kafka-topics --create --bootstrap-server=localhost:9092 --topic=teste --partitions=3```

> PARA CONSUMIR DE UM TÓPICO VIA TERMINAL:
> 
> ```kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste```
