# Project Webhook Inspector API

Um serviço para capturar e inspecionar requisições webhook, permitindo visualizar detalhes como headers, corpo, parâmetros de query e outras informações relevantes.

## 🚀 Funcionalidades Back-end

<img width="1916" height="1031" alt="back-end" src="https://github.com/user-attachments/assets/c9c5a699-4b9c-4223-b48d-04af8e333bed" />

- **Captura de Webhooks**: Recebe e armazena requisições HTTP de qualquer tipo
- **Inspeção Detalhada**: Registra headers, corpo, método, status code, IP de origem e mais
- **API REST**: Endpoints para listar e visualizar webhooks recebidos
- **Documentação Interativa**: API documentada com Swagger/Scalar
- **Paginação**: Suporte a cursor-based pagination para listagem eficiente
- **Tipagem Forte**: Desenvolvido com TypeScript e validação Zod

## 🛠 Tecnologias Back-end

- **Runtime**: Node.js
- **Framework**: Fastify
- **Banco de Dados**: PostgreSQL
- **ORM**: Drizzle ORM
- **Validação**: Zod
- **Documentação**: Scalar API Reference
- **Migrations**: Drizzle Kit
- **TypeScript**: Tipagem estática

## 🚀 Funcionalidades Front-end

<img width="1916" height="930" alt="front end" src="https://github.com/user-attachments/assets/9a9b867d-11c3-430b-b310-be2d3ac92497" />

- **Interface Dividida**: Painel lateral com lista de webhooks e painel principal para detalhes
- **Inspeção Detalhada**: Visualize método, headers, parâmetros de query e corpo da requisição
- **Syntax Highlighting**: Destaque de sintaxe para JSON no corpo das requisições
- **Timestamps**: Histórico com timestamps relativos
- **Gerenciamento**: Exclua webhooks individualmente
- **Cópia Rápida**: Copie a URL de captura com um clique
- **Scroll Infinito**: Carregamento automático conforme você scrolla
- **Tema Escuro**: Interface com tema escuro otimizada para desenvolvedores

## 🛠 Tecnologias Front-end

- **Frontend**: React 18 + TypeScript
- **Roteamento**: TanStack Router
- **Estado**: TanStack Query
- **Estilização**: Tailwind CSS
- **Ícones**: Lucide React
- **UI**: Radix UI (Checkbox)
- **Syntax Highlighting**: Shiki
- **Painéis Redimensionáveis**: React Resizable Panels
- **Utilidades**: date-fns, tailwind-merge, tailwind-variants
- **Validação**: Zod

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
