# Developer Portfolio

A full-stack developer portfolio focused on backend and full-stack engineering.

## Planned Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- React Router
- TanStack Query
- React Hook Form and Zod

### Backend
- Node.js
- Express
- TypeScript
- Prisma ORM
- PostgreSQL
- Zod
- Pino

### Development Environment
- npm workspaces monorepo
- Docker Compose
- Vite HMR for the frontend
- `tsx watch` for the Express API
- PostgreSQL with a persistent development volume

## Planned Applications

```text
apps/
├── web/    # Public portfolio and admin interface
└── api/    # Express REST API
```

## Development Goal

The development environment should start with a single Docker Compose command. Source code changes should automatically refresh the frontend or restart the backend without requiring manual container restarts in normal development.

## Project Management

Development work is organized in GitHub Issues. Epic issues contain checklists linking to their implementation issues.
