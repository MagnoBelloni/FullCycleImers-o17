# GeekShoping - Semana Fullstack Master

Este projeto foi construído durante o curso "Imersão Fullstack FullCycle" na [FullCycle](https://imersao.fullcycle.com.br/evento/).

## Início

### Pré-requisitos:

Você precisa das seguintes tecnologias instaladas na sua máquina:

- Node
- Go

## Como rodar

### Docker compose

- docker compose up -d

### NestJS API

- Rodar o
- Dentro da pasta nestjs-api:
  - npm i
  - npm run fixture(roda um pequeno seed com alguns dados de produtos)
  - npm run start:dev

### Payment Go RabbitMQ Consumer

- Dentro da pasta PAYMENT/cmd/payment
  - go run main.go

## Como Testar

Existe o arquivo api.http que contém as rotas necessárias para autenticar e executar ações nos endpoints, com a extensão REST Client é possivel executar as ações direto do VSCode

## Construído com:

- [Go](https://go.dev) - The Go programming language is an open source project to make programmers more productive.
- [NestJS](https://nestjs.com) - NestJS is a framework for building efficient, scalable Node.js web applications.
- [MySQL](https://www.mysql.com) - The world's most popular open source database.
- [RabbitMQ](https://www.rabbitmq.com/) - A webinar on high availability and data safety in messaging.

## Autor:

- **Magno Belloni** - [LinkedIn](https://www.linkedin.com/in/magnobelloni/)
