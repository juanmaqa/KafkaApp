# KafkaApp basic Spring Boot application to Publishing and Consuming Messages from Topics

After clone this project follow the next steps:

1- Run Kafa in docker.
  docker run -p 2181:2181 -p 9092:9092 --name servicekafka  -e ADVERTISED_HOST=127.0.0.1  -e NUM_PARTITIONS=3 -d johnnypark/kafka-zookeeper
2- Configure your run/debug configs
3- Run the project
4- Using postman POST a message e.g. http://localhost:8888/kafkaapp/post?msg=Distillery
