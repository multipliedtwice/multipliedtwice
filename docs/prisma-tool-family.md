# Prisma tool family

| Tool | Role | Public reference |
| --- | --- | --- |
| [prisma-generator-express](https://github.com/multipliedtwice/prisma-generator-express) | Generates CRUD routes, OpenAPI, and optional integrations for Express, Fastify, and Hono. | [Guide](https://multipliedtwice.github.io/prisma-generator-express/guide/) |
| [prisma-guard](https://github.com/multipliedtwice/prisma-guard) | Generates validation, reusable query and write shapes, projections, caller variants, and tenant scope. | [Docs](https://multipliedtwice.github.io/prisma-guard/) |
| [prisma-sql](https://github.com/multipliedtwice/prisma-sql) | Runs supported generated read queries through PostgreSQL or SQLite native clients. | [Docs and benchmarks](https://multipliedtwice.github.io/prisma-sql/) |
| [prisma-query-builder-ui](https://github.com/multipliedtwice/prisma-query-builder-ui) | Provides a local visual Prisma query builder and playground. | [Repository](https://github.com/multipliedtwice/prisma-query-builder-ui) |
| [prisma-rbac](https://github.com/multipliedtwice/prisma-rbac) | Adds role-based model and action permissions through a Prisma Client extension. | [Repository](https://github.com/multipliedtwice/prisma-rbac) |

## Existing demo

The published [`packages/demo`](https://github.com/multipliedtwice/prisma-generator-express/tree/master/packages/demo) is an Express 5, Prisma 6, PostgreSQL Docker Compose reference app. Its schema configures `prisma-guard` and `prisma-generator-express`; its application wires the generated routers, a guard-extended Prisma client, an optional `postgres` connector for `prisma-sql`, and the query-builder package.

See the [demo README](https://github.com/multipliedtwice/prisma-generator-express/blob/master/packages/demo/readme.md) for the source map.
