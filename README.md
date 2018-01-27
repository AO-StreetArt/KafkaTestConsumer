# Kafka Test Consumer

Super simple and basic Kafka Consumer for use in CI Testing

## Use

Examples:

`python KafkaDockerConsumer.py _dvs localhost:9092`

`sudo docker run -i -t -d --network=dvs --name=test_consumer aostreetart/kafkadockerconsumer:dev _dvs queue:9092`

## TO-DO
* Add support for receiving ZMQ Messages from 0-Meter and asserting on the Kafka messages based on the input
