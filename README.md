# Project Portfolio Management (PPM Dashboard)

Lightweight dashboard and sample UI for an enterprise Project & Portfolio Management platform.

## What's here

- Frontend: Next.js + React + Tailwind (folder: `frontend`)
- Backend: example notes + Prisma schema (folder: `backend`)
- Basic GitHub Actions workflow: `.github/workflows/ci.yml`

## Quick start (frontend)

Requirements: Node.js 18+ (Node 20 recommended), npm

Install and run the frontend locally:

```bash
cd frontend
npm install
npm run dev
```

Run lint and type checks:

```bash
cd frontend
npm run lint
npx tsc --noEmit -p tsconfig.json
```

Build for production:

```bash
cd frontend
npm run build
```

## CI

A simple GitHub Actions workflow runs lint, TypeScript checks and build for the `frontend` on push and PRs.

## Notes

- This repo contains example data and UI in `frontend/app/page.tsx` used for prototyping.
- Remove or relocate large example constants to separate modules if you want to reduce ESLint warnings.

