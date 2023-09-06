# Desafio - Explorando IA Generativa em um Pipeline de ETL com Python

## O que é?
Este repositório contém um script Python que extrai uma lista de IDs de usuário a partir de um arquivo CSV, utiliza a API do OpenAI GPT-4 para gerar mensagens de marketing personalizadas para cada usuário e, em seguida, atualiza a lista de "news" de cada usuário na API do Santander Dev Week 2023.

## Repositório da API
O repositório da API da Santander Dev Week 2023 pode ser encontrado em https://github.com/digitalinnovationone/santander-dev-week-2023-api.

## Executando o codigo
Para executar este código, siga estas etapas:

1. Clone o repositório da API da Santander Dev Week 2023.
2. Certifique-se de que você tenha o Python instalado em seu ambiente.
3. Instale as bibliotecas necessárias, como Pandas, Requests e OpenAI, usando pip install.
4. Substitua as variáveis **sdw2023_api_url** e **openai_api_key** com os valores corretos.
5. Certifique-se de que o arquivo 'SDW2023.csv' esteja na mesma pasta do seu script.
6. Execute o código.

Este código extrairá os IDs de usuário, gerará mensagens de marketing personalizadas e atualizará a API da Santander Dev Week com as mensagens geradas para cada usuário.

**Lembre-se de cuidar da segurança de suas chaves de API e dos dados do usuário ao executar o código em um ambiente de produção.**
