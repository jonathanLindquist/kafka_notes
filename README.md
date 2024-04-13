# Kafka Notes

## Docs

In order to have the Kafka scripts on your env $PATH, `brew install kafka` should automatically add them. [Here](https://access.redhat.com/documentation/en-us/red_hat_openshift_streams_for_apache_kafka/1/topic/015379fc-1863-4ba0-b224-a8b92b57efe1) is a link to explaining where they are places.

Confluence has a basic starting guide on commands and usages [here](https://docs.confluent.io/kafka/operations-tools/kafka-tools.html), you just won't need the `.sh` after since the names will be on your $PATH.

## Basic cmds

```sh
kafka-broker-api-versions --bootstrap-server <host>:<port> --version
```