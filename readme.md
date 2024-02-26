# Projeto Azure Cognitive Search

##  INÍCIO

## 🔨 Passo a passo

## 01 - Passo 1: Criando recurso do Azure AI Search:

![1 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/0.png)

## Passo 2: Apos criar o recurso no AI Search, crie outro no Azure AI services:

![2 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/2.png)

## Passo 3: Crie agora uma conta de armazenamento:

![3 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/3.png)

![4 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/4.png)

## Passo 4: Permitindo acesso anônimo ao Blob:
Para a leitura dos dados no passo a passo desse projeto precisamos permitir o acesso anônimo ao blob para simplificar e facilitar nossas implementações, Após criar o seu Storage, entre no mesmo e navegue até a guia SETTINGS > CONFIGURATION seguindo os passos abaixo:

![5 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/5.png)

## Passo 5: Criando o Container:
Navegue até a guia DATA STORAGE > CONTAINERS, para criar o contanier dentro do storage e adicionar as pesquisas que seram analisadas pelo AI SERVICE e insira os dados para a implementação.

![6 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/6.png)

![7 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/7.png)

## Passo 6: Importação e indexação dados para o AI SEARCH:

Agora voce ira importar os dados que você inseriu e configurou no seu STORAGE, volte para o AI SEARCH e siga os passos abaixo:

![8 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/8.png)

## Passo 7: Consultando o índice:

Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:

![9 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/9.png)


```search=*&$count=true``` (verifica se a indexação esta funcionando e mostra os documentos)

![10 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/10.png)

```search=locations:'Chicago'``` (Consulta as ocorrencias acontecidas em Chicado)

![11 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/11.png)

```search=sentiment:'negative'``` (Consulta as ocorrencias com sentimento negativo)

![12 passo](https://github.com/Mathsilvaw/Projeto-IASearchAZURE/blob/main/outputs/12.png)


### Considerações Finais

As ferramentas de inteligência artificial do Azure facilitam a consulta em documentos, pesquisas e etc, agilizando ainda mais a consulta de satisfação de empresas sobre seus produtos e serviços.

## LINKS E REFERÊNCIAS

- [GitDOC](https://git-scm.com/book/pt-br/v2)
- [Azure](azure.microsoft.com)
- [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
