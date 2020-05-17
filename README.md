# kafka-workshop

- Try to understand what you're doing, and why. Really.

<img src="https://media.makeameme.org/created/one-does-not-5b913b.jpg" width="150"></img>

- Download the source

```
wget https://downloads.apache.org/kafka/2.5.0/kafka_2.12-2.5.0.tgz

tar -xzf kafka_2.12-2.5.0.tgz
cd kafka_2.12-2.5.0
```
- Start a quick & dirty single-node Zookeeper instance
```
bin/zookeeper-server-start.sh config/zookeeper.properties&
```

- Start the Kafka Server
```
bin/kafka-server-start.sh config/server.properties&
```



