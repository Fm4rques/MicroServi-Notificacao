# Projeto de Microserviço de Notificações

## Descrição: 
        Este projeto é um microserviço de notificações que permite o envio de mensagens em tempo real para os usuários. Ele foi desenvolvido utilizando a arquitetura de microsserviços, com foco na escalabilidade e na comunicação assíncrona. O microserviço de notificações é responsável por receber as requisições de envio de mensagens e distribuí-las aos usuários conectados.

## Estrutura do Projeto:

O projeto está organizado na seguinte estrutura de diretórios:

/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── exemplos/
│   │   │   │   │   ├── controllers/
│   │   │   │   │   │   ├── [Arquivos relacionados aos controladores]
│   │   │   │   │   ├── models/
│   │   │   │   │   │   ├── [Arquivos relacionados aos modelos]
│   │   │   │   │   ├── services/
│   │   │   │   │   │   ├── [Arquivos relacionados aos serviços]
│   │   │   │   │   ├── repositories/
│   │   │   │   │   │   ├── [Arquivos relacionados ao acesso aos dados]
│   │   │   │   │   ├── messages/
│   │   │   │   │   │   ├── [Arquivos relacionados às mensagens]
│   │   │   │   │   ├── exceptions/
│   │   │   │   │   │   ├── [Arquivos relacionados às exceções]
│   ├── resources/
│   │   ├── [Arquivos de configuração]
│   ├── test/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── exemplos/
│   │   │   │   │   ├── controllers/
│   │   │   │   │   │   ├── [Arquivos de teste dos controladores]
│   │   │   │   │   ├── services/
│   │   │   │   │   │   ├── [Arquivos de teste dos serviços]
│   │   │   │   │   ├── repositories/
│   │   │   │   │   │   ├── [Arquivos de teste dos acessos aos dados]
├── [Arquivos de configuração adicionais]
├── [Outros diretórios e arquivos relevantes]

## Tecnologias Utilizadas:

O projeto utiliza as seguintes tecnologias:

Linguagem de programação: Java
Framework: Spring Boot
Banco de Dados: PostgreSQL
Biblioteca de mensageria: RabbitMQ
Ferramentas adicionais: Maven, Swagger

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

JDK 11 ou superior
Maven
Docker (para executar o RabbitMQ e o PostgreSQL em containers)

## Como Executar

Siga as etapas abaixo para executar o projeto localmente:

Clone o repositório para sua máquina local.
Navegue até o diretório raiz do projeto.
Execute o comando mvn spring-boot:run para iniciar o microserviço.
Acesse http://localhost:8080/swagger-ui.html para visualizar a documentação da API e interagir com o serviço de notificações.
Projeto aprendizagem Tópicos Avançado - Micro Serviço de Notificação
