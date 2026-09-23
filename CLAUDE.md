# CLAUDE.md

This repository is a reusable React frontend starter template, not an application. It provides a neutral component foundation for future projects.

## Stack

- React + Vite + TypeScript
- Tailwind CSS for styling
- shadcn/ui components, already installed as source code (not an npm package)
- Lucide as the icon library

## Conventions

- shadcn/ui components live in `src/components/ui` — reuse them instead of installing another UI component library.
- Shared utilities live in `src/lib`.
- The `@/*` import alias resolves to `src/*` (configured in `tsconfig.json`, `tsconfig.app.json`, and `vite.config.ts`).
- Do not modify or replace the shadcn architecture (`components.json`, the `src/components/ui` structure, the alias setup) unnecessarily.

## Commands

- `npm run dev` — start the local dev server
- `npm run build` — type-check and build for production
- `npm run lint` — lint with oxlint
