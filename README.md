# Elysia with Bun runtime

## Getting Started
To get started with this template, simply paste this command into your terminal:
```bash
bun create elysia imdb-api
```

## Development
To start the development server run:
```bash
bun run dev
```
or
```bash
npm run dev
```

## Planetscale
- Database: `movies`
- Shadow Database: `shadow`

## Prisma
To start the Prisma run:
```bash
bun add prisma
bunx prisma init --datasource-provider mysql
bunx prisma migrate dev --name init
bunx prisma db seed
bunx prisma generate --data-proxy
```
## Swagger
To start the Swagger run:
```bash
bun add @elysiajs/swagger
```
- htttp://localhost:3000/v1/swagger

Open http://localhost:3000/ with your browser to see the result.
