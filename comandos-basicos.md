# Comandos Básicos do Docker

Anotações práticas para consulta rápida de gerenciamento de containers e imagens.

## 1. Gerenciamento de Containers
* `docker run -d -p 8080:80 --name meu-nginx nginx` -> Baixa e inicia um container do servidor web Nginx em segundo plano (`-d`), mapeando a porta `8080` do PC para a `80` do container.
