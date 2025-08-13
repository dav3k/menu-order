# Menu Ordering – Full‑Stack Scaffold (Next.js + Express + Postgres)

## Quick start (Docker)
```bash
cp .env.example .env
docker compose up --build -d
# (first run may take a minute to generate Prisma client & run migrations)
docker compose exec api node src/seed.js
open http://localhost:3000
```

## Quick start (local without Docker)
```bash
cp .env.example .env
npm install
npm run db:generate
npm run db:migrate
npm run db:seed
npm run dev
```
