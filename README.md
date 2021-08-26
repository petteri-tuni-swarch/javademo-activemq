## Overview

This is an example of how use the Java JMS api with ActiveMQ.

## Prereqs

- Install Java SDK
- Install [Maven](http://maven.apache.org/download.html) 

## Building

Run:

    mvn install

## Running the Examples

In one terminal window run:

    java -cp target/activemq-demo1-0.1-SNAPSHOT.jar example.Listener

In another terminal window run:

    java -cp target/activemq-demo1-0.1-SNAPSHOT.jar example.Publisher

You can control to which server the examples try to connect to by
setting the following environment variables: 

... for Runtunx ~petteri/mq ActiveMQ installation:

````
export ACTIVEMQ_PORT=62616
export ACTIVEMQ_HOST=127.0.0.1
export ACTIVEMQ_USER=admin
export ACTIVEMQ_PASSWORD=admin
````
... 61616 is more average port.

