# Kafka-Spring-Sample

- INSTALL KAFKA ON MAC - https://www.tutorialkart.com/apache-kafka/install-apache-kafka-on-mac/


- RUN ZOOKEEPER (in Terminal) 
    - sh bin/zookeeper-server-start.sh config/zookeeper.properties
- START KAFKA (in Terminal) 
    - sh bin/kafka-server-start.sh config/server.properties	
- CREATE TOPIC (in Terminal) 
    - bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example
- CREATE PRODUCER (in Terminal)
    - bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic Kafka_Example --from-beginning
    
    
    
    Source : https://www.youtube.com/watch?v=NjHYWEV_E_o  