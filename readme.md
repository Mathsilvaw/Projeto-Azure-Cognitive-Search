# Projeto Análise de Sentimentos com Language Studio

##  INÍCIO

Através deste recurso a Inteligência Artificial irá analisar textos afim de descobrir o sentimento e satisfação do usuário que o escreveu e assim como suas opiniões.

## 🔨 Passo a passo

### 01 - Passo 1: Criando recurso do Azure AI Search:

![Primeiro passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/1.PNG)

### Passo 2: Apos criar o recurso no AI Search, crie outro no Azure AI services:

![Segundo passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/2.png)

### Passo 3: Crie agora uma conta de armazenamento:

![Terceiro passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/3.png)

![Quinto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/5.png)

### Passo 4: Permitindo acesso anônimo ao Blob:

Para a leitura dos dados no passo a passo desse projeto precisamos permitir o acesso anônimo ao blob para simplificar e facilitar nossas implementações, Após criar o seu Storage, entre no mesmo e navegue até a guia SETTINGS > CONFIGURATION seguindo os passos abaixo:

![Quinto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/5.png)

### Passo 5: Criando o Container:

Navegue até a guia DATA STORAGE > CONTAINERS, para criar o contanier dentro do storage e adicionar as pesquisas que seram analisadas pelo AI SERVICE e insira os dados para a implementação.

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)

### Passo 6: Importação e indexação dados para o AI SEARCH:

Agora voce ira importar os dados que você inseriu e configurou no seu STORAGE, volte para o AI SEARCH e siga os passos abaixo:

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)

Passo 7: Consultando o índice:

Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)


```search=*&$count=true``` (verifica se a indexação esta funcionando e mostra os documentos)

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)

```search=locations:'Chicago'``` (Consulta as ocorrencias acontecidas em Chicado)

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)

```search=sentiment:'negative'``` (Consulta as ocorrencias com sentimento negativo)

![Sexto passo](https://github.com/Mathsilvaw/Projeto-sentimentoIA/blob/main/Output/6.png)


### Considerações Finais

As ferramentas de inteligência artificial do Azure facilitam a consulta em documentos, pesquisas e etc, agilizando ainda mais a consulta de satisfação de empresas sobre seus produtos e serviços.

## LINKS E REFERÊNCIAS

- [GitDOC](https://git-scm.com/book/pt-br/v2)
- [Azure](azure.microsoft.com)
- [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
