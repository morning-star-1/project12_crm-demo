# CRM Demo (Next.js + Prisma)

CRM Demo is a small CRM dashboard for sales teams built with Next.js and Prisma to track accounts, contacts, deals, and activities.

## Features
- Accounts, contacts, and deals
- Activity tracking
- SQLite dev database with seed data

## Screenshot
![Screenshot](docs/screenshot.png)

Replace `docs/screenshot.png` with a real screenshot or GIF.

## Quickstart
### Prerequisites
- Node.js 20+
- npm

### Run locally
```bash
cp .env.example .env
npm install
npx prisma migrate dev --name init
npx prisma db seed
npm run dev
```

Open `http://localhost:3000`.

## Configuration
- `DATABASE_URL` in `.env`

## Tests
```bash
npm test
```
