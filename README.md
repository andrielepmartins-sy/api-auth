# API com Autenticação e Prisma

Este projeto consiste em uma API desenvolvida durante os estudos de **Desenvolvimento de Sistemas**, utilizando **Node.js**, **TypeScript** e **Prisma ORM**.

A aplicação possui funcionalidades relacionadas à autenticação de usuários, gerenciamento de usuários e criação de posts, utilizando uma estrutura organizada com **Controllers, Services, Routes e Middlewares**.

## Funcionalidades

Durante o desenvolvimento do projeto foram abordados os seguintes conceitos:

- Criação de uma API com Node.js
- Utilização do TypeScript
- Criação e gerenciamento de rotas
- Separação da aplicação em Controllers e Services
- Autenticação de usuários
- Criação de Middlewares
- Proteção de rotas
- Cadastro e gerenciamento de usuários
- Criação e gerenciamento de posts
- Validação de dados
- Integração com banco de dados
- Utilização do Prisma ORM
- Criação e execução de migrations

## Estrutura do Projeto

```text
04_Auth_Middleware/
├── generated/
│   └── prisma/
│       ├── internal/
│       └── models/
│           └── User.ts
│
├── prisma/
│   ├── migrations/
│   │   └── 2026030224413_init/
│   │       └── migration.sql
│   ├── migration_lock.toml
│   └── schema.prisma
│
├── src/
│   ├── controllers/
│   │   ├── auth.controller.ts
│   │   ├── post.controller.ts
│   │   └── user.controller.ts
│   │
│   ├── lib/
│   │   ├── prisma.ts
│   │   └── validateInputs.ts
│   │
│   ├── middlewares/
│   │   └── auth.middleware.ts
│   │
│   ├── routes/
│   │   ├── auth.routes.ts
│   │   └── user.routes.ts
│   │
│   ├── services/
│   │   ├── auth.service.ts
│   │   ├── post.service.ts
│   │   └── user.service.ts
│   │
│   └── server.ts
│
├── dev.db
├── eslint.config.ts
├── package.json
├── prisma.config.ts
├── teste.http
├── tsconfig.json
└── README.md
