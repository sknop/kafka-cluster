# kafka-cluster
Creates a docker cluster for Kafka with Zookeeper, Schema registry and other services.
Uses local data directory to be able to restart the docker image without data loss.

Use with docker-compose:

Run setup.sh first to create local directories
Run docker-compose up -d

Shutdown with docker-compose down

