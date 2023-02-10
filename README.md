# Testes automatizados com Cypress - Básico

👋 Seja bem-vindo(a)!

É muito bom tê-lo(a) aqui. Tenho certeza que você vai adorar este curso. ❤️

## O que você vai aprender

Durante o curso de testes automatizados com Cypress (básico), você vai aprender:

- Como configurar um projeto Cypress do zero
- Como visitar páginas locais e remotas
- Como lidar com os elementos mais comuns encontrados em aplicações web
- Como testar _upload_ de arquivos
- Como realizar as mais diversas verificações de resultados esperados
- Como criar comandos customizados
- Como lidar com links que abrem em outra aba do navegador
- Como rodar testes simulando as dimensões de um dispositivo móvel
- Como resolver os mesmos problemas de diferentes formas, conhecendo a [API do Cypress](https://docs.cypress.io/api/table-of-contents)
- Como executar os testes em um _pipeline_ de integração contínua sempre que mudanças ocorrerem no código da aplicação (ou dos testes)
- Como criar uma documentação mínima para seu projeto de testes automatizados

## Vamos começar?

Vá para a seção [estrutura do curso](./lessons/_course-structure_.md).

___

Este é mais um curso da [**Escola Talking About Testing**](https://udemy.com/user/walmyr).


# cy-data-test

Curso de Testes automatizados com Cypress - Básico

# Pré-requisitos

Antes de começar, garanta que os seguintes sistemas estejam instalados em seu computador.

- [git](https://git-scm.com/) (estou usando a versão `2.34.1` enquanto escrevo esta aula)
- [Node.js](https://nodejs.org/en/) (estou usando a versão `v16.13.2` enquanto escrevo esta aula)
- npm (estou usando a versão `8.3.2` enquanto escrevo esta aula)
- [Google Chrome](https://www.google.com/intl/pt_br/chrome/) (estou usando a versão `98.0.4758.80 (Official Build) (x86_64)` enquanto escrevo esta aula)
- [Visual Studio Code](https://code.visualstudio.com/) (estou usando a versão `1.64.0` enquanto escrevo esta aula) ou alguma outra IDE de sua preferência

> **Obs.:** Recomendo utilizar as mesmas versões, ou versões mais recentes dos sistemas listados acima.
>
> **Obs. 2:** Ao instalar o Node.js o npm é instalado junto. 🎉
>
> **Obs. 3:** Para verificar as versões do git, Node.js e npm instaladas em seu computador, execute o comando `git --version && node --version && npm --version` no seu terminal de linha de comando.
>
> **Obs. 4:** Deixei links para os instaladores na lista de requisitos acima, caso não os tenha instalados ainda.


## Instalação

Na raiz do projeto, execute o comando `npm install cypress@9.5.1 --save-dev` (ou `npm i cypress@9.5.1 -D` para a versão curta)


## Testes

### Desktop

Para testar em modo headless:
`npm test` ou `npm t`

Para rodar em modo interativo:
`npm run cy:open`

### Mobile

Para testar em modo headless:
`npm test:mobile`

Para rodar em modo interativo:
`npm run cy:open:mobile`


___

This project was created with 💚 by [Walmyr](https://walmyr.dev).
