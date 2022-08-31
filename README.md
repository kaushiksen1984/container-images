docker login -u kaushiksen1984 -p GITHUB_TOKEN ghcr.io

docker build -t kafka-producer .

docker tag kafka-producer:latest ghcr.io/kaushiksen1984/container-images/kafka-producer:latest

docker push ghcr.io/kaushiksen1984/container-images/kafka-producer

https://github.com/users/kaushiksen1984/packages/container/package/container-images%2Fkafka-producer
