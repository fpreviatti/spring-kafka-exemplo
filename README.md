# Spring com Kafka

Para montar as 3 instâncias docker do producer, na pasta docker com o git bash aberto:

docker-compose -f kafka-docker-compose.yml up -d

<img src="https://github.com/fpreviatti/spring-kafka-exemplo/blob/main/docker.png" height="auto">

Verificar se criou:

docker container list -a

<img src="https://github.com/fpreviatti/spring-kafka-exemplo/blob/main/list.png" width="400px" height="auto">

Kafkadrop, acessar via localhost:19000

<img src="https://github.com/fpreviatti/spring-kafka-exemplo/blob/main/kafdrop.png" width="400px" height="auto">