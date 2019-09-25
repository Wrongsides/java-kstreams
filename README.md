Little experiment with kafka streams copied from the confluent examples. Also rolled a java producer and consumer to demonstrate the WordProducer in action.  

to have a go follow these steps:

1) bring up kafka with ```docker-compose up -d```
2) run the WordProducer
3) run the WordCount
4) run the CountConsumer

ctrl+c to close apps and ```docker-compose down -v``` to tear down / clean up kafka.