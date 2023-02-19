# Simulator

## Rodar a aplicação

Importante: A aplicação do Apache Kafka deve estar rodando primeiro.

Execute os comandos:

```
docker-compose up -d
# Entrar no container
docker-compose exec app bash
# Rodar a aplicação Golang
go run main.go
```
