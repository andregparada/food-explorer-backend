# food-explorer-backend

O projeto é um menu interativo para um restaurante fictício.
O objetivo final é que seja uma aplicação com dois tipos de usuários: clientes e administradores. Os clientes podem buscar pratos e visualizar e os administradores, adcionar e editar os pratos.
 
Stack:
  O projeto utiliza Node.js e React.js

Estrutura:
  Backend: na pasta src
    server.js reúne a lógica dew funcionamento geral do backend
    routes reúne as rotas das requisições
    controllers reúne as lógicas
    database onde se cria e armazena o banco de dados
    o projeto usa knex para lidar com a conexão com o banco

Como rodar dev:
  fazer download do arquivo
  Baixar o noje.js
  Rodar usando comando: npm install
  rodar: npm run dev
  O projeto estará rodando na PORT 3333
  Para testar o papel de admin, deve mudar o papel no banco de dados ou entrar com o perfil: andre@email.com senha: 123
