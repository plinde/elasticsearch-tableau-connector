This is a 'stub' repo which just contains a Dockerfile used to build a Docker image against https://github.com/mradamlacey/elasticsearch-tableau-connector

Build with the usual Docker bits...

```
docker build -t "plinde/elasticsearch-tableau-connector" .
docker tag 703c917dc696 plinde/elasticsearch-tableau-connector:latest
docker login --username=plinde
docker push plinde/elasticsearch-tableau/connector
```
