# react-vite-ts-boilerplate

React 19 + TypeScript + Vite starter, with linting (Oxlint), formatting (Prettier), tests (Vitest + Testing Library) and CI. Intended as a base for a local SonarQube POC.

## Scripts

| Command                           | Description                                   |
| --------------------------------- | --------------------------------------------- |
| `npm run dev`                     | Start dev server                              |
| `npm run build`                   | Typecheck and production build                |
| `npm run typecheck`               | TypeScript check                              |
| `npm run lint`                    | Oxlint                                        |
| `npm run format` / `format:check` | Prettier                                      |
| `npm test` / `test:coverage`      | Vitest (coverage writes `coverage/lcov.info`) |

Requires Node 22+ (see `.nvmrc`).
