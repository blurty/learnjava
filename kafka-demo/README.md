# kafka-demo

## compile

> mvn compile

the command will generate two class files in target/classes/, which executable consumer and producer exists.

## run

First, open a terminal and start the consumer:

> mvn exec:java -Dexec.mainClass="consumer.ConsumerFastStart"


Second, open another terminal and start the producer:

> mvn exec:java -Dexec.mainClass="producer.ProducerFastStart"