# Elasticsearch Sample

## Start

```shell
docker compose up -d
# docker compose down -v
```

URL: <http://localhost:5601/>

| user    | passowrd         |
| ------- | ---------------- |
| elastic | NVCY4GatYLViDFDD |

## Run App

```shell
./gradlew :app:bootRun -x test
```

## Note

1. [Start a multi-node cluster with Docker Compose](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-compose-file)
