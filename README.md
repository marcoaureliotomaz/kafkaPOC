# Projeto de Estudo: Java +Spring + Apache Kafka

Bem-vindo ao repositório do projeto de estudo sobre Java  e Apache Kafka! Este projeto foi desenvolvido com o objetivo de explorar e entender como desenvolver serviços em java para consumir e produzir mensagens de tópicos na solução  de mensageria Kafka.
O projeto faz parte do curso Kafka: produtores, consumidores e streams da Alura
Link do curso: 

## Tecnologias Utilizadas

- **Java 17**: Linguagem de programação utilizada para o desenvolvimento da aplicação.
- **Apache Kafka**: Plataforma de streaming distribuída usada para construção de pipelines de dados e sistemas de mensageria.

## Estrutura do Projeto

 **ecommmerce**: Contém as classes de produtores e consumidores.
- **EmailService**: Simula um consumidor que irá gerenciar o envio de email.
- **FraudDetectorService**: Simula um consumidor que irá analisar os pedidos de venda.
- **LogService**: Simula um consumidor que irá realizar Log das mensagens.
- **NewOrderMain**: Produz as mensagens no tópicos de novos pedidos .



1. **Clone o repositório**:

    ```sh
    git clone https://github.com/marcoaureliotomaz/kafkaPOC
    cd kafkaPOC
    ```

2. **Configuração do Kafka**: Certifique-se de ter uma instância do Apache Kafka em execução. Você pode usar o arquivo docker-compose.yml na pasta resources do projeto para isso:

    ```sh
    docker-compose -f docker-compose.yml up -d
    ```

## Uso

1. **Produzir mensagens**:
2. **Consumir mensagens**:


## Contribuição

Sinta-se à vontade para contribuir com este projeto. Por favor, envie pull requests e relatar problemas no GitHub.
