# How to start Kafka

```
cd kafka-release/kafka_2.13-3.2.1
bin/zookeeper-server-start.sh config/zookeeper.properties
bin/kafka-server-start.sh config/server.properties
```

# Read from topic
```
bin/kafka-console-producer.sh --topic cristianrb --bootstrap-server localhost:9092
```