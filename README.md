# Rabbitmq

## Setup

```bash
docker run --rm -d --hostname my-rabbit --name some-rabbit -p 8080:15672 -p 5672:5672 rabbitmq:3-management
```

## Run
```bash
go run main.go
```

## Teardown
```bash
docker stop some-rabbit
```