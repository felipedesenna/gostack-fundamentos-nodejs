<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio: Fundamentos do NodeJS
</h3>

# Índice

- [Sobre](#sobre)
- [Como Usar](#como-usar)
- [Critérios de aceite](#criterios)

<a id="sobre"></a>

## :memo: Sobre

O **Desafio** é uma API desenvolvida para realização de cadastro e listagem de transações bancárias em memória com execução dos métodos HTTP desenvolvidos com NodeJS, Typescript e Express.

A API foi construída durante o **Bootcamp GoStack** realizado pela [Rocketseat](https://rocketseat.com.br/).

<a id="como-usar"></a>

## :computer: Como usar

1 - Faça o download ou clone do projeto:

```sh
  $ git clone https://github.com/felipedesenna/gostack-fundamentos-nodejs.git
```

2 - Executando o projeto:

```sh
  # Instale as dependências da aplicação
  $ npm install / yarn

  ## Back-end / API
  $ npm run dev:server / yarn dev:server

  ## Executar test
  $ npm run test / yarn test
```
<a id="criterios"></a>

## :white_check_mark: Critérios de aceite

Para esse desafio os seguintes testes foram utilizados como critérios de aceite:

- **`should be able to create a new transaction`**: Para que esse teste passe, sua aplicação deve permitir que uma transação seja criada, e retorne um json com a transação criada.

- **`should be able to list the transactions`**: Para que esse teste passe, sua aplicação deve permitir que seja retornado um objeto contendo todas as transações junto ao balanço de income, outcome e total das transações que foram criadas até o momento.

- **`should not be able to create outcome transaction without a valid balance`**: Para que esse teste passe, sua aplicação não deve permitir que uma transação do tipo `outcome` extrapole o valor total que o usuário tem em caixa, retornando uma resposta com código HTTP 400 e uma mensagem de erro no seguinte formato: `{ error: string }`

- ### **Observação**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/download/)** instalado na máquina e para gerenciar os pacotes da aplicação o **[NPM](https://www.npmjs.com/get-npm)** ou **[Yarn](https://yarnpkg.com/getting-started/install)**.
