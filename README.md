# Project Webhook Inspector API

Um serviço para capturar e inspecionar requisições webhook, permitindo visualizar detalhes como headers, corpo, parâmetros de query e outras informações relevantes.

## 🚀 Funcionalidades

- **Captura de Webhooks**: Recebe e armazena requisições HTTP de qualquer tipo
- **Inspeção Detalhada**: Registra headers, corpo, método, status code, IP de origem e mais
- **API REST**: Endpoints para listar e visualizar webhooks recebidos
- **Documentação Interativa**: API documentada com Swagger/Scalar
- **Paginação**: Suporte a cursor-based pagination para listagem eficiente
- **Tipagem Forte**: Desenvolvido com TypeScript e validação Zod

## 🛠 Tecnologias

- **Runtime**: Node.js
- **Framework**: Fastify
- **Banco de Dados**: PostgreSQL
- **ORM**: Drizzle ORM
- **Validação**: Zod
- **Documentação**: Scalar API Reference
- **Migrations**: Drizzle Kit
- **TypeScript**: Tipagem estática

## 📋 Pré-requisitos

- Node.js 18+
- PostgreSQL
- npm ou yarn

## ⚙️ Instalação

1. **Clone o repositório**

```bash
git clone https://github.com/EduardoMendes418/Full-Stack-WebHook-Inspector-IA.git
cd webhook-inspector
pnpm install

NODE_ENV=development
PORT=3333
DATABASE_URL=***

# Execute as migrations
npm run db:push

# Desenvolvimento
pnpm run dev

# Produção
pnpm run build
pnpm start

http://localhost:3333/docs

```
