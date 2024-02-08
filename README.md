# Aplicação Node.js com Fastify, Redis, Prisma e WebSocket

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/genssauer/websocket-redis.git
```

2. Instale as dependências:

```bash
npm install
```

## Configuração

1. Crie um `.env` e configure as variáveis de ambiente:
```json
DATABASE_URL="postgresql://docker:docker@localhost:5432/polls?schema=public"
```

## Uso

1. Inicie os contêineres Docker:

```bash
docker-compose up -d
```

2. Inicie o servidor:

```bash
npm run dev
```

## Funcionalidades

- API REST com Fastify
- WebSocket para comunicação em tempo real
- Integração com Redis e Prisma
