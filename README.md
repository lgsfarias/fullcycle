# Desafio Docker e Go

Esse é um projeto simples que consiste em criar uma imagem Docker que execute um programa em Go que imprime a mensagem "Full Cycle Rocks!!".

A imagem que criei para este projeto pode ser encontrada neste link: https://hub.docker.com/r/lgsfarias/fullcycle/

## Requisitos

- Docker 20.10 ou superior

## Executando o projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório em sua máquina
2. Na raiz do projeto, execute o comando `docker build -t fullcycle .` para criar a imagem Docker
3. Execute o comando `docker run fullcycle` para executar a imagem e ver a mensagem "Full Cycle Rocks!!" impressa no terminal

## Publicando a imagem no Docker Hub

Para publicar a imagem no Docker Hub, siga os passos abaixo:

1. Certifique-se de ter uma conta no Docker Hub e de estar logado no terminal
2. Na raiz do projeto, execute o comando `docker build -t <seu-usuario>/fullcycle .` para criar a imagem com o nome do seu usuário do Docker Hub
3. Execute o comando `docker push <seu-usuario>/fullcycle` para enviar a imagem para o Docker Hub

## Considerações finais

Este é um projeto simples para demonstrar a criação de uma imagem Docker com um programa em Go. Sinta-se à vontade para modificar e melhorar o projeto de acordo com suas necessidades.
