## :rocket: modulo01 - Introdução ao Node.js

Este é um projeto introdutório ao Node.js no <b>Bootcamp GoStack da Rocketseat</b> onde trabalhamos de forma simples na construção de um CRUD, fazendo uso dos Query params e Body dos métodos para acessar os dados enviados pelo usuário e tratar as respostas. 

Junto às requisições, trabalhamos também com os middlewares, que funcionam como interceptadores das requisições (e ai temos os dois tipos, que tratam localmente um método específico ou todas as requisições) para validar, tratar e retornar dados antes de seguir com a requisição.

## Rodando o projeto:

1 - Baixe o projeto e abra ele utilizando seu editor preferido.

2 - Abra o console e digite `npm install` (ou `yarn install`, se o tiver instalado) para fazer a instalação dos pacotes necessários (dependências).

3 - Após isso, digite no console `npm run dev` ou `yarn dev`(se tiver o yarn instalado), para começar a rodar o servidor com a aplicação.

Uma vez tendo o servidor ativo e rodando, pode acessar os métodos `get` através do seu navegador no endereço `http://localhost:3000/`, ou todos os outros utilizando ferramentas como Postman ou Insomnia para enviar dados em formato Json no corpo da requisição, ou nos parâmetros de rota.

# Exemplo: 

Enviando o Json abaixo para a rota `http://localhost:3000/users` utilizando o método `POST`, conseguirá cadastrar um usuário novo. Note que a aplicação não trabalha com armazenamento de dados, então eles são guardados somente em variáveis locais. Uma vez reiniciado o servidor, ela volta aos seu valor inicial.

`
{
  name: 'Guilherme'
}
`

Um projeto bem simples, mas que marca meu primeiro contato com Node.js ♥.
