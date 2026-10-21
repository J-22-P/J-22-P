# Hi, I'm Pongsathorn

Full-stack developer based in Bangkok. I like building complete products end to end: the UI, the API, the database, background jobs, tests and deployment.

My main project right now is **[NOSION](https://github.com/J-22-P/nosion)**, a daily-life app that puts tasks, money and habits on one "Today" page, so you don't have to jump between three apps to see your day. I built it alone as a full portfolio project. [Live demo](https://nosion-staging-web.vercel.app/login) (click "ลองใช้ทันที" for a demo account with sample data, no sign-up needed).

## What I built in NOSION

- **Monorepo** with pnpm + Turborepo: a Next.js web app, a NestJS API, a BullMQ worker, and shared packages for contracts, UI tokens, emails and notifications
- **Quick capture:** type a plain sentence like `ส่งรายงาน พรุ่งนี้ 5 โมง !high #work` and the app parses it into a task, expense or habit
- **Tasks, finance, habits, calendar and weekly review**, with recurring tasks, budgets, bill reminders, focus timer and a ⌘K command palette
- **Auth:** email + Argon2id, JWT, and OAuth with Google and GitHub, with several accounts linked to one user
- **GitHub integration:** assigned issues and PRs become tasks, milestones show on the calendar, tasks close when the PR merges
- **Public API** with read-only or read-write API keys and Swagger docs
- **Notifications:** email and web push, due-date reminders and a daily digest, run as background jobs
- **PWA** that installs on a phone, works offline, supports light/dark themes and Thai/English
- **Testing:** unit and integration tests with Vitest and Supertest, end-to-end and visual tests with Playwright, accessibility checks with axe, Lighthouse audits
- **CI/CD:** GitHub Actions for lint, typecheck, tests and build, separate staging and production deploys, and a rollback workflow
- **Ops:** Docker Compose for local dev, Prometheus alerts, structured logging with pino, architecture decision records and system diagrams in `docs/`

## Tech stack

**Languages:** TypeScript, JavaScript, SQL, HTML, CSS

**Frontend:** React, Next.js, Tailwind CSS, TanStack Query, Zustand, React Hook Form, Zod, next-intl

**Backend:** Node.js, NestJS, Express, REST APIs, Swagger/OpenAPI, BullMQ

**Database:** PostgreSQL, Prisma, Redis, SQLite

**Auth & security:** JWT, OAuth 2.0 (Google, GitHub), Argon2id, bcrypt, Helmet, rate limiting

**Testing:** Vitest, Playwright, Supertest, axe-core, Lighthouse

**DevOps:** Docker, GitHub Actions, Vercel, Supabase, Upstash, Fly.io, Prometheus, Turborepo, pnpm

## Other projects

- **[Disaster Prediction Dashboard](https://github.com/J-22-P/Environmental_Rick_Project):** drought and flood risk from environmental data, comparing four ML models. React, TypeScript, Recharts
- **[READ A ROAD](https://github.com/J-22-P/Web-Novel---Read-A-Road):** online novel platform for readers, writers and admins. Node.js, Express, SQLite, JWT

## Contact

[Email](mailto:pongsathorn.junt@gmail.com) · [LinkedIn](https://www.linkedin.com/in/your-linkedin)
