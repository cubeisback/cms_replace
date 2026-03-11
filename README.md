# cms_replace

# CMS Replace

Modern replacement for WordPress-based CMS using a fullstack JavaScript architecture.

## Stack

- Next.js
- TypeScript
- Prisma
- PostgreSQL
- Redis
- Tailwind CSS
- Docker

## Features

- Custom CMS
- Admin panel
- Full text search
- File uploads
- Real-time notifications
- Authentication system

## Project Structure

```
apps/
  web/       - public website
  admin/     - admin panel

packages/
  database/  - prisma schema and migrations
  ui/        - shared UI components
  config/    - shared configs
```

## Requirements

- Node.js >= 20
- Docker
- pnpm

## Installation

Clone repository:

```
git clone https://github.com/USERNAME/cms_replace.git
cd cms_replace
```

Install dependencies:

```
pnpm install
```

Start docker services:

```
docker compose up -d
```

Run development server:

```
pnpm dev
```

## Development

Start web:

```
pnpm --filter web dev
```

Start admin:

```
pnpm --filter admin dev
```

## Database

Run migrations:

```
pnpm prisma migrate dev
```

Open Prisma Studio:

```
pnpm prisma studio
```

## License

MIT
