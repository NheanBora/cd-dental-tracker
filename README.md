# Dental Income & Expense Tracker

A web app for managing dental practice finances, built with Next.js, Prisma, PostgreSQL/SQLite, Tailwind, and shadcn/ui.

## Features
- Patient Management (CRUD)
- Treatments/Cases tracking
- Invoices with partial payments
- Expense tracking
- Reports with charts (Recharts)
- i18n (Khmer/English), currency (KHR/USD)
- Filters, search, reminders, CSV export/import

## Setup
1. Clone the repo: `git clone https://github.com/your-username/dental-tracker.git`
2. Install dependencies: `pnpm i`
3. Set up `.env` (see `.env.example`)
4. Run migrations: `npx prisma migrate dev --name init`
5. Seed database: `pnpm db:seed`
6. Start dev server: `pnpm dev`

## Deployment
Deploy on Vercel:
1. Connect repo to Vercel.
2. Set environment variables (`DATABASE_URL`, etc.).
3. Deploy.

## Scripts
- `pnpm dev`: Run locally
- `pnpm build`: Build for production
- `pnpm test`: Run Vitest tests
- `pnpm db:seed`: Seed sample data
