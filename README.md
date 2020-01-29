Simple Kafka-Spark System 
----------------------------
To start the system clone this repository and make `docker-compose up`.

## Zookeeper
  - name  : zookeeper
  - IP    : 172.25.0.11
  - PORTS : 2181

## Kafka Broker 1
  - name  : kafka1
  - IP    : 172.25.0.12
  - PORTS : 8080, 9092

## Kafka Broker 2
  - name  : kafka2
  - IP    : 172.25.0.13
  - PORTS : 8080, 9092

## Kafka Manager
  - name  : kafka_mager
  - IP    : 172.25.0.14
  - PORTS : 9000

## Spark Master
  - name  : spark-master
  - IP    : 172.25.0.15
  - PORTS : 8080, 7077

## Spark Worker 1
  - name  : spark-worker-1
  - IP    : 172.25.0.16
  - PORTS : 8081

## Spark Worker 2
  - name  : spark-worker-2
  - IP    : 172.25.0.16
  - PORTS : 8081

