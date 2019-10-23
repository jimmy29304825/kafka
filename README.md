## kafka
This repo can start kafka cluster container include:
  * kafka
  * zookeeper
  * restproxy
  * ksql-server
  * ksql-cli
  * jupyter
  * schema-registry

if you set these container on cloud, you have to change the enviorment parameter of kafka container.
```bash
nano docker-compose.yml
  # KAFKA_ADVERTISED_HOST_NAME: [CloudIP]
  # KAFKA_ADVERTISED_LISTENERS: PLAINTEXT://[CloudIP]:9092
```
