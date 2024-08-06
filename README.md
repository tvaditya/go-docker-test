# Imagem Docker Go Rocks!!

Este repositório contém uma aplicação simples em Go que imprime "Go Rocks!!" quando executada. A aplicação é empacotada em uma imagem Docker e hospedada no Docker Hub como `tvaditya/fullcycle`.

## Índice

- [Introdução](#introdução)
- [Pré-requisitos](#pré-requisitos)
- [Baixando a Imagem Docker](#baixando-a-imagem-docker)
- [Executando a Imagem Docker](#executando-a-imagem-docker)
- [Usando Docker Compose](#usando-docker-compose)
- [Verificação e Depuração](#verificação-e-depuração)
- [Licença](#licença)

## Introdução

Este projeto demonstra como construir e usar uma aplicação simples em Go com Docker. A aplicação em Go, quando executada, imprime a mensagem "Go Rocks!!". A imagem Docker é construída usando um build multi-stage para manter o tamanho da imagem final mínimo.

## Pré-requisitos

- Docker instalado na sua máquina. Você pode baixar e instalar o Docker [aqui](https://docs.docker.com/get-docker/).

## Baixando a Imagem Docker

Para baixar a imagem Docker do Docker Hub, execute o seguinte comando no seu terminal:

```bash
docker pull tvaditya/fullcycle
