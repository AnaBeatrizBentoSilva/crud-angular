# CRUD com Angular e API Fake (JSON Server)

Este repositório contém um projeto CRUD desenvolvido com Angular no frontend e um backend fake utilizando JSON Server. O objetivo é simular uma API REST para realizar operações de criação, leitura, atualização e exclusão de dados de forma simples e eficiente.

## 🚀 Objetivo
Criar uma aplicação CRUD funcional, utilizando:
- Angular: Estruturação e lógica da aplicação.
- TypeScript: Tipagem e segurança no desenvolvimento.
- JSON Server: Simulação de uma API REST para persistência de dados.
- Node.js: Ambiente para executar o servidor da API fake.

## 🔒 Conceitos Abordados
- Comunicação entre frontend e backend utilizando HTTP Requests.
- Manipulação de serviços e requisições assíncronas (GET, POST, PUT, DELETE).
- Boas práticas na estruturação de um projeto Angular.
- Simulação de banco de dados com JSON Server.

## 📂 Estrutura do Repositório

```plaintext
.
├── backend/
│   ├── node_modules/
│   ├── db.json
│   ├── package-lock.json
│   └── package.json
├── frontend/
│   ├── node_modules/
│   └── src/
│   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── directives/
│   │   │   ├── views/
│   │   │   ├── app-routing.module.ts
│   │   │   ├── app.component.html
│   │   │   ├── app.component.ts
│   │   │   └── app.module.ts
│   │   ├── assets/
│   │   │   │   └── logo.png
│   │   │   ├── img/
│   │   │   └── .gitkeep
│   │   ├── environments/
│   │   │   ├── environment.prod.ts
│   │   │   └── environment.ts
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── main.ts
│   │   ├── polyfills.ts
│   │   └── styles.css
│   ├── .gitignore
│   ├── angular.json
│   ├── browserslist
│   ├── package-lock.json
│   ├── package.json
│   ├── README.md
│   ├── tsconfig.app.json
│   └── tsconfig.json
└── README.md
