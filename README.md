# Kafka Products: IBM Event Streams & Red Hat AMQ Streams Demo

### Pre-requisites
* Must have an IBM Event Streams instance and topic set up
* Must have a Red Hat AMQ Streams instance and topic set up

### General Information
* IBM Event Streams is using SASL_SSL authentication in this app configuration to connect to the Kafka cluster
* Red Hat AMQ Streams is using SSL authentication in this app configuration to connect to the Kafka cluster

### To run locally: 
* At the project root directory, do `./gradlew clean build`
* Then do `docker-compose up --build`
