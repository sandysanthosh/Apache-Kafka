#### Apache-Kafka:

```

-> kafka cluster:

producer - >  source system,source system,source system,source system,

Brokers->  Kafka

Consumer ->Hadoop, Security Systems, Real-Time Monitoring, Dat warehouse

Kafka Decouples Data Pipelines


-> Zookeeper:

-> Producer:

-> Kafka Broker 1:

Topic 1
Topic 2

-> Kafka Template:

-> Spring Boot Security

-> Bank ACcount withdraw changes

-> SMS Application,
-> Email Application

-> KafkaListener:

-> Kafka we need to commit the offset after reading message

-> Step for Kafka:

1. Create spring boot app with spring kafka starter

2. Kafkaconsumerconfig - SPRING bean configuration - @EnableKafka

3. Start Zookeper, Kafka, Producer app to test the consumer app


spring boot kafka:

Dependency:
	
Spring for Apache Kafka
Spring Web

Application.properties:

kafka.broker.address=localhost:9092
server.port=8080

Class:

Kafka Consumer

@Configuration
@EnableKafka

public class KafkaConsumerCOnfig{

@Value("${kafka.broker.address}")
private String kafkaBrokerAddress;

@Bean
public ConsumerFactory<String, String> consumerFactory(){

Map<String, Object> configMap = new HashMap<>();
configMap.put(ConsumerConfig.
configMap.put(ConsumerConfig.
configMap.put(ConsumerConfig.
configMap.put(ConsumerConfig.

}

```


##### There are five major APIs in Kafka:


```

Producer API – Permits an application to publish streams of records.
Consumer API – Permits an application to subscribe to topics and processes streams of records.
Connector API – Executes the reusable producer and consumer APIs that can link the topics to the existing applications.
Streams API – This API converts the input streams to output and produces the result.
Admin API – Used to manage Kafka topics, brokers, and other Kafka objects.

```



